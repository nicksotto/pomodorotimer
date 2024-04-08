<div align="center">
  <img alt="Pomotroid" src="../../.github/images/pomotroid-title.png" width="800px">
</div>
<div align="center">
  <img alt="Pomotroid in action" src="../../.github/images/pomotroid-screens.png" width="800px">
</div>
<p align="center">簡約且美觀的Pomotroid番茄鐘</p>

---

**語言切換**：en <a href="../../README.md">English</a>

​				   zh_CN <a href="./README_zh.md">简体中文</a>

​				   zh_TW <a href="./README_tw.md">繁體中文</a>

------

**目录**

- [概述](#overview)
- [功能](#features)
  - [主題](#themes)
- [安裝](#install)
  - [下載](#download)
  - [macOS](#homebrew)
  - [Windows](#scoop)
  - [Windows](#appget)
- [藍圖(規劃)](#roadmap)
- [開發](#development)
  - [配置環境](#build-setup)
- [許可證](#license)

## 概述

Pomotroid是一個簡單且可配置的番茄定時器。它的目的是在提供一種美觀且可靠的軟件來使用番茄工作法關注生產力。

Pomotroid還處於早期階段，所以歡迎並感謝反饋和貢獻！:seedling:

## 功能

- 自定義時間和次數(持久進行)
- 迷人的定時器提醒聲音（可選）
- 桌面通知（可選）
- 最小化到托盤（可選）
- 除了預設的幾個主題還包括創建自定義主題的能力
- 計時器活動日誌記錄

### 主題

Pomotroid提供了許多主題。它也是主題化的，允許你定制它的外觀。

![Screenshots of Pomotroid using various themes](https://rosyrain.oss-cn-hangzhou.aliyuncs.com/img2/202404081638800.png)

請訪問【主題文檔】 [theme documentation](./docs/themes/themes.md)查看官方主題的完整列表，並獲得創建屬於自己的主題。

## 安裝

###  下載

請從[releases](https://github.com/Splode/pomotroid/releases) 頁面,下載最新版本的Pomotroid番茄鐘。

Pomotroid 適用於**Windows**、**Mac OSX**和**Linux**。

### Homebrew

您可以使用 [Homebrew](https://brew.sh) 在**macOS**上安裝Pomotroid:

```sh
brew install --cask pomotroid
```

### Scoop

您可以使用 [scoop ](https://scoop.sh/)在**Windows**上安裝Pomotroid:

```sh
scoop install https://raw.githubusercontent.com/Splode/pomotroid/master/pomotroid.json
```

### AppGet

您可以使用 [AppGet](https://appget.net/)在**Windows**上安裝Pomotroid:

```sh
appget install pomotroid
```

## 藍圖

:memo: 有關優化和拓展功能的未來規劃:

- 迷你模式

## 開發

Pomotroid 是依靠[Vue.js](https://github.com/vuejs/vue), [Electron](https://github.com/electron/electron), 和 [electron-vue](https://github.com/SimulatedGREG/electron-vue)進行開發的。

*提示: 根據您的操作系統設置，您可能會在安裝時收到安全警告。這與Pomotroid是一個未簽名（認證）的應用程序有關。你可以通過研究蘋果和微軟的代碼簽名來了解更多。*

### 配置環境

```bash
# 安裝依賴 npm install
npm i

# 啟動項目（在本機的9080端口進行服務熱加載）
npm run dev

# 打包項目
npm run build
```

## 許可證

MIT &copy; [Christopher Murphy](https://github.com/Splode)
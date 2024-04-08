<div align="center">
  <img alt="Pomotroid" src="../../.github/images/pomotroid-title.png" width="800px">
</div>
<div align="center">
  <img alt="Pomotroid in action" src="../../.github/images/pomotroid-screens.png" width="800px">
</div>
<p align="center">简约且美观的Pomotroid番茄钟</p>

---

**语言切换**：en <a href="../../README.md">English</a>

​				   zh_CN <a href="./README_zh.md">简体中文</a>

​				   zh_TW <a href="./README_tw.md">繁體中文</a>

------

**目录**

- [概述](#overview)
- [功能](#features)
  - [主题](#themes)
- [安装](#install)
  - [下载](#download)
  - [macOS](#homebrew)
  - [Windows](#scoop)
  - [Windows](#appget)
- [蓝图(规划)](#roadmap)
- [开发](#development)
  - [配置环境](#build-setup)
- [许可证](#license)

## 概述

Pomotroid是一个简单且可配置的番茄定时器。它的目的是在提供一种美观且可靠的软件来使用番茄工作法关注生产率。

Pomotroid还处于早期阶段，所以欢迎并感谢反馈和贡献！:seedling:

## 功能

- 自定义时间和次数(持久进行)
- 迷人的定时器提醒声音（可选）
- 桌面通知（可选）
- 最小化到托盘（可选）
- 除了默认的几个主题还包括创建自定义主题的能力
- 计时器活动日志记录

### 主题

Pomotroid提供了许多主题。它也是主题化的，允许你定制它的外观。

![Screenshots of Pomotroid using various themes](https://rosyrain.oss-cn-hangzhou.aliyuncs.com/img2/202404081638800.png)

请访问【主题文档】 [theme documentation](./docs/themes/themes.md) 查看官方主题的完整列表，并获得创建属于自己的主题。

## 安装

### 下载

请从[releases](https://github.com/Splode/pomotroid/releases) 页面,下载最新版本的Pomotroid番茄钟。

Pomotroid 适用于**Windows**、**Mac OSX**和**Linux**。

### Homebrew

您可以使用 [Homebrew](https://brew.sh) 在**macOS**上安装Pomotroid:

```sh
brew install --cask pomotroid
```

### Scoop

您可以使用 [scoop ](https://scoop.sh/)在**Windows**上安装Pomotroid:

```sh
scoop install https://raw.githubusercontent.com/Splode/pomotroid/master/pomotroid.json
```

### AppGet

您可以使用 [AppGet](https://appget.net/)在**Windows**上安装Pomotroid:

```sh
appget install pomotroid
```

## 蓝图

:memo: 有关优化和拓展功能的未来规划:

- 迷你模式

## 开发

Pomotroid 是依靠[Vue.js](https://github.com/vuejs/vue), [Electron](https://github.com/electron/electron), 和 [electron-vue](https://github.com/SimulatedGREG/electron-vue)进行开发的。

*提示: 根据您的操作系统设置，您可能会在安装时收到安全警告。这与Pomotroid是一个未签名（认证）的应用程序有关。你可以通过研究苹果和微软的代码签名来了解更多。*

### 配置环境

```bash
# 安装依赖 npm install
npm i

# 启动项目（在本机的9080端口进行服务热加载）
npm run dev

# 打包项目
npm run build
```

## 许可证

MIT &copy; [Christopher Murphy](https://github.com/Splode)
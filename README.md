![logo](./docs/public/images/arch.svg)

# archlinux 简明指南

[📖 阅读地址](https://arch.icekylin.online/)

:books: 本指南包含 archlinux 安装、配置、维护等，帮助新手快速上手。

:heart: 让 archlinux 成为你的常用系统吧！

<p>
  <a
    href="https://github.com/NakanoMikuOrg/arch-guide"
    target="_blank"
    rel="noopener noreferrer"
  >
    <img
      alt="Lines of code"
      src="https://img.shields.io/tokei/lines/github/NakanoMikuOrg/arch-guide"
    />
  </a>
  <a
    href="https://github.com/NakanoMikuOrg/arch-guide"
    target="_blank"
    rel="noopener noreferrer"
  >
    <img
      alt="arch-guide"
      src="https://travis-ci.com/NakanoMikuOrg/arch-guide.svg?branch=main"
    />
  </a>
  <a
    href="https://github.com/NakanoMikuOrg/arch-guide"
    target="_blank"
    rel="noopener noreferrer"
  >
    <img
      alt="GitHub last commit"
      src="https://img.shields.io/github/last-commit/NakanoMikuOrg/arch-guide"
    />
  </a>
  <a
    href="https://github.com/NakanoMikuOrg/arch-guide"
    target="_blank"
    rel="noopener noreferrer"
  >
    <img
      alt="GitHub Repo stars"
      src="https://img.shields.io/github/stars/NakanoMikuOrg/arch-guide?style=social"
    />
  </a>
  <a
    href="https://gitee.com/nakano-miku/arch-guide/stargazers"
    target="_blank"
    rel="noopener noreferrer"
  >
    <img
      src="https://gitee.com/nakano-miku/arch-guide/badge/star.svg?theme=white"
      alt="Gitee Repo stars"
    />
  </a>
  <a
    href="https://tongji.baidu.com/web/welcome/ico?s=e7059486ad3b16e21ea7058836c51b9b"
    target="_blank"
    rel="noopener noreferrer"
  >
    <img
      src="https://img.shields.io/badge/Baidu-%E7%BB%9F%E8%AE%A1-blue"
      alt="百度统计"
    />
  </a>
  <a
    href="https://arch.icekylin.online/postscript/contributor-covenant.html"
    target="_blank"
    rel="noopener noreferrer"
  >
    <img
      alt="Contributor Covenant"
      src="https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg"
    />
  </a>
</p>

## :construction: 文档施工中

## :green_book: 相关信息

本指南派生自 [Arch Linux 安装使用教程](https://github.com/ArchLinuxStudio/ArchLinuxTutorial)。

## :computer: 本地运行

### Pacman

```shell
sudo pacman -S nodejs pnpm # 安装 nodejs 和 PnpM
git clone https://github.com/NakanoMikuOrg/arch-guide.git
cd ./arch-guide
pnpm i
pnpm docs:dev
```

### HomeBrew

```shell
brew install pnpm # 安装 PnpM
git clone https://github.com/NakanoMikuOrg/arch-guide.git
cd ./arch-guide
pnpm i
pnpm docs:dev
```

### Scoop

```powershell
scoop install nodejs # 安装 nodejs
scoop install pnpm # 安装 PnpM
git clone https://github.com/NakanoMikuOrg/arch-guide.git
cd ./arch-guide
pnpm i
pnpm docs:dev
```

其它系统请参阅 [PnpM 中文文档](https://pnpm.io/zh/installation) 安装 `PnpM`。

## :bell: 隐私提醒

本站使用百度统计和 Google Analytics 分析流量。访问即同意它们的隐私政策。

## :seedling: 参与贡献

欢迎对指南内容以及网站源码做出贡献，也欢迎对本指南的上游文档做出贡献。

更多信息请参阅 [贡献指南](https://arch.icekylin.online/postscript/contribute.md)。

## :gem: 版权说明

网站源代码采用 MIT
许可证；未经特殊说明，本作品采用 [知识共享署名-相同方式共享 4.0 国际许可协议](https://creativecommons.org/licenses/by-sa/4.0/deed.zh)
进行许可。

更多信息请参阅 [版权说明](https://arch.icekylin.online/postscript/copyright.md)。

## :cake: 贡献者

<a href="https://github.com/NakanoMikuOrg/arch-guide/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=NakanoMikuOrg/arch-guide" alt="contributors"/>
</a>

## :star: Star 历史

[![Star History](https://starchart.cc/NakanoMikuOrg/arch-guide.svg)](https://starchart.cc/NakanoMikuOrg/arch-guide)

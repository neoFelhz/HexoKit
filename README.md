# HexoKit

受够了 npm 源国内速度太慢？受够了从 Github clone landscape 主题时速度不尽人意？

现在，忘记这一切吧！使用 HexoKit，快速在 Windows 上安装并初始化一个 Hexo 并开始使用！

-----

## 介绍

这个脚本会将 npm 源暂时换成淘宝的 cnpm 源加快 Hexo 的安装速度，当安装完以后会切换回 npm 官方源。

这个脚本会将已经初始化好了的 Hexo 工程拉回本地，然后使用 npm install 安装 repo 中使用 `package.json` 定义的其它依赖。

## 依赖

HexoKit 和 Hexo 便携版不同，HexoKit 只是为了方便你快速安装 Hexo，所以 Hexo 的基本依赖仍然需要手动安装。

- 安装 [NodeJS](https://nodejs.org/zh-cn/)，Windows 用户建议直接使用安装程序安装。
- 安装 Git。对于 Windows 用户，你可以从 Git 的[官网](https://git-scm.com/download/win)下载它。

> 由于众所周知的原因，从上面的链接下载 `git for windows` 最好挂上一个代理，否则下载速度十分缓慢。你也可以参考这个[页面](https://github.com/waylau/git-for-win)，收录了 `git for windows` 的国内镜像地址。

## 教程
- 在需要安装 Hexo 的目录下，右键 `Git Bash Here`，执行：

```bash
curl http://git.oschina.net/neoFelhz/hexokit/raw/master/install.sh | sh
```

> 当然你也可以：
> - [下载安装脚本](http://git.oschina.net/neoFelhz/hexokit/raw/master/install.sh)
> - 将脚本移动到你需要安装 Hexo 的目录。右键 `Git Bash Here`。
> - 在 Git Bash 中执行 `./install.sh`

- 执行的过程大概需要 3 分钟左右，根据你所在的网络环境决定。
- 当安装完以后会显示你的 Hexo 的版本号、Hexo 命令行的版本号、所在平台的 OS 版本号等有关信息。
- Hexo 在 HexoKit 文件夹内安装完成。你现在可以将 HexoKit 文件夹重命名。

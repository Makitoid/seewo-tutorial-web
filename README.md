<div align="center">

<image src="https://avatars.githubusercontent.com/u/160447230?s=200&v=4" height="64" />

# 电教委入门指南

从小白到高手，轻松玩转班级一体机

### [🌐 电教委入门指南网站](https://tutorial.misaka.space/)

#### [💬 希沃售后业绩冲击部入群测试](https://exam.misaka.space/)

</div>

这是电教委入门指南网站的源码仓库。

网站使用 [VuePress](https://vuepress.vuejs.org/) 和 [VuePress Theme Hope](https://theme-hope.vuejs.press/) 构建与生成。

## 运行环境
- 编辑器：推荐使用 [Visual Studio Code](https://code.visualstudio.com/)
- Node.js: 推荐最新长期支持版 (LTS)
- pnpm: 推荐最新版本
  - 在安装 Node.js 之后，在终端中输入以下命令启用 corepack (Windows 用户需要使用管理员权限):
    ```bash
    corepack enable
    ```
  > [!tip]
  > 推荐你使用 pnpm 作为项目管理器，因为 VuePress 和 VuePress Theme Hope 都是通过 pnpm 来管理依赖的。
  >
  > pnpm 的一些功能可以保证你拥有正确的依赖，并且它能加速安装。

## 本地运行
1. 克隆仓库并在此目录打开终端

2. 安装依赖

    ```bash
    pnpm install
    ```

3. 启动开发服务器

    ```bash
    pnpm run docs:dev
    ```

4. `Crtl + 单击`终端输出的相关链接即可自动在浏览器打开，当本地文档做出更改时，浏览器中的文档将自动刷新。

## 常用命令
- `pnpm run docs:dev` 启动开发服务器
- `pnpm run docs:build` 构建项目并输出
- `pnpm docs:clean-dev` 清除缓存并启动开发服务器
- `docs:update-package` 更新依赖包

> 终止开发服务器：
>
> 在终端中连续两次按下 `Ctrl + C`。

本文档使用了 [vuepress-plugin-md-enhance](https://plugin-md-enhance.vuejs.press/zh/) 的一些扩展语法，请尽量直接编辑 Markdown 文件，而不是使用可视化 Markdown 编辑器。

## 致谢

感谢以下为本文档做出贡献的同学：

<a href="https://github.com/seewo-geek/seewo-tutorial-web/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=seewo-geek/seewo-tutorial-web&max=1000" alt="贡献者名单"/>
</a>

## 许可证

<p xmlns:cc="http://creativecommons.org/ns#" >本文档以 <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt=""></a> 许可协议授权。</p>

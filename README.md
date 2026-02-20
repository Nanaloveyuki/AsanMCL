# AsanMCL

[简体中文](./README.md)

高性能，现代化的MC启动器

> 请注意：当前为实验性阶段，很有可能会遇到如下情况：
> 1. 依赖不完全导致崩溃
> 2. 编译时大量warn
> 3. 大量冗余沉积代码和引用
> 4. 不明所以的功能项

## 技术栈

语言和框架：
- 前端：vue3 + vite + typescript
- 后端：rust + tauri2

包管理器：
- 前端：npm + pnpm
- 后端：rustup + cargo

## 如何使用

> 还没有公开发布的 Release 包，欢迎大佬来 Pr

1. 从 [Github Release](https://github.com/Asankilp/AsanMCL/releases) 下载适配您设备的安装包或 `AppImage`

2. 启动并安装到本地（`AppImage` 可以忽略这一步）

3. 从应用列表或文件夹启动，然后就可以使用了

## 如何贡献

1. fork 当前仓库

2. 使用 `git clone` 命令从 `github` 中您所 fork 的仓库克隆

3. 使用您钟爱的编辑工具打开克隆的仓库

4. 编辑代码或是其他内容

安装环境
```bash
cd AsanMCL # 打开文件夹 
npm install
npm run tauri dev
```

> 在编辑代码前建议使用 `npm install` 命令获取当前所需要的依赖，同时你需要安装 [pnpm](https://www.pnpm.cn/)，这是运行开发模式所必须的。
> 如果您正在使用如 Arch Linux 系的 Linux 发行版，那么有可能出现 `Tauri` 依赖不完全安装的情况，您可能单独安装`Tauri`

5. commit 并推送到您所 fork 的仓库

6. 提交 Pull Request（`Pr`）到主仓库请求合并
# c.project01

C / C++ 练习项目仓库。

## 说明

本仓库目前为初始化骨架，仅包含 `README.md` 与 `.gitignore`。
后续把源码、工程文件放入本目录后，按下面的流程提交即可。

## 提交流程

```bash
git add .
git commit -m "描述本次改动"
git push
```

## 忽略规则

`.gitignore` 已按 Visual Studio C++ 项目的常见约定配置，会排除以下内容：

- 构建输出：`x64/`、`x86/`、`Debug/`、`Release/`、`build/`、`out/`
- Visual Studio 缓存与用户配置：`.vs/`、`*.user`、`*.suo`
- 编译产物：`*.exe`、`*.pdb`、`*.obj`、`*.ilk`
- 系统文件：`Thumbs.db`、`desktop.ini`

如果你的项目改用其他语言或工具链，请相应调整 `.gitignore`。

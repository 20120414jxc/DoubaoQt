# 豆包客户端

## 项目简介

这是一个基于Qt WebEngineWidgets开发的豆包网页套壳应用，能够加载豆包官方网页并保存登录状态，提供类似于桌面应用的体验。

## 功能特点

- 加载豆包官方网页（https://www.doubao.com）
- 持久化存储登录状态，无需每次重新登录
- 支持高DPI屏幕
- 响应式窗口大小

## 技术实现

- 使用Qt 6框架开发
- 基于WebEngineWidgets加载网页
- 使用QWebEngineProfile实现登录状态持久化
- 存储路径：临时目录下的DoubaoClient文件夹

## 构建方法

1. 确保已安装Qt 6开发环境
2. 使用CMake构建项目：

```bash
mkdir build
cd build
cmake ..
make
```

3. 运行应用：

```bash
./DoubaoClient
```

## 注意事项

- 首次运行时会在临时目录创建存储文件夹
- 登录状态会保存在本地，确保隐私安全
- 若遇到权限问题，可能需要以管理员权限运行

## 许可证

MIT License
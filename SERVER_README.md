# 本地服务器使用说明

## 快速开始

### 方法一：使用启动脚本（推荐）

**Windows系统：**
双击运行 `start-server.bat` 文件

**Linux/Mac系统：**
```bash
chmod +x start-server.sh
./start-server.sh
```

### 方法二：直接使用Node.js命令

```bash
node server.js
```

## 访问网页

服务器启动后，在浏览器中访问：

- http://localhost:3000
- http://127.0.0.1:3000

## 停止服务器

在运行服务器的终端窗口中，按 `Ctrl + C` 停止服务器。

## 服务器配置

默认端口：`3000`

如果需要修改端口，请编辑 `server.js` 文件中的 `PORT` 变量。

## 功能特性

- 支持静态文件服务（HTML、CSS、JavaScript等）
- 自动识别文件类型并设置正确的MIME类型
- 支持Three.js等外部库的加载
- 简单易用的命令行界面

## 注意事项

1. 确保已安装Node.js（v12.0.0或更高版本）
2. 确保端口3000未被其他程序占用
3. 服务器启动后，请保持终端窗口打开


# Micro-System
基于microbit的小车同步控制、回传程序

## 使用
1. 安装编译环境：[yotta](https://lancaster-university.github.io/microbit-docs/offline-toolchains/)
2. 初始化依赖
```bash
yt target bbc-microbit-classic-gcc
```

3. 编译本程序
```bash
yt clean
yt build
```
4. 上传到microbit

直接将工程目录下的```\build\bbc-microbit-classic-gcc\source\micro-system-combined.hex```拖放到microbit的闪存

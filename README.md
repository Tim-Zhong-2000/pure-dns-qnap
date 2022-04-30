# PureDns-qnap

为威联通 QNAP 系统构建 PureDns 安装包

## 配置

参考 PureDns 配置，修改 `shared/setting.json`，修改监听地址，上游等参数。

## 编译

在当前目录执行 `qbuild` 进行打包，打包后安装包在 `build/pure-dns_<version>_<arch>.qpkg`

## 安装

在威联通系统中打开App Center，点击右上角安装，选择上一步编译好的qpkg文件，安装完成。
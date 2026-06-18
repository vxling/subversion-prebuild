# libsvn Windows Prebuilt Dev Kit

基于 Apache Subversion 官方源码自动化构建的 Windows x64 开发套件

- 支持 file:// / http:// / https:// 仓库访问
- 已裁剪：BDB、Python/Java/Perl/SWIG 绑定、svnserve、mod_dav_svn
- 仅输出 C/C++ 开发所需头文件、导入lib、运行DLL

## 上游项目

- Subversion: https://subversion.apache.org/
- APR / APR-Util / APR-Iconv: https://apr.apache.org/
- Serf: https://serf.apache.org/
- zlib: https://zlib.net/
- SQLite: https://sqlite.org/
- OpenSSL: https://www.openssl.org/

## 开源协议

所有 Apache 基金会组件遵循 Apache License 2.0；
zlib 使用 zlib/png 协议；SQLite 为公有领域；OpenSSL 使用 Apache 2.0 附带 SSLeay 声明。
分发包内 licenses/ 文件夹包含全部协议原文。

## 免责声明

本预编译包为社区自动化构建产物，**非 Apache 软件基金会官方发布**，无任何明示或隐含担保，使用风险自负。本仓库不隶属于 Apache 软件基金会。

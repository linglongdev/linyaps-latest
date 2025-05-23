<!--
SPDX-FileCopyrightText: 2023 UnionTech Software Technology Co., Ltd.

SPDX-License-Identifier: LGPL-3.0-or-later
-->

# 查看运行中的应用

`ll-cli ps`命令可以查看正在运行的如意玲珑应用。

查看`ll-cli ps`命令的帮助信息：

```bash
ll-cli ps --help
```

`ll-cli ps` 命令的帮助信息如下：

```text
列出正在运行的应用程序
用法: ll-cli ps [选项]

Options:
  -h,--help                   打印帮助信息并退出
  --help-all                  展开所有帮助

如果在使用过程中遇到任何问题，
您可以通过此项目向如意玲珑项目团队报告错误：https://github.com/OpenAtom-Linyaps/linyaps/issues
```

查看正在运行的应用，运行`ll-cli ps`命令：

```bash
ll-cli ps
```

`ll-cli ps`命令输出如下：

```text
应用              容器ID        进程ID
org.dde.calendar  4e3407a8a052  1279610
```

# ORE CLI
English | [简体中文](README_ZH-CN.md)




1.此版本是在原有矿池 Kriptikz/ore-hq-server 版本上面修改的

2.只修改了服务端

-.加上jito稳定提交
-.修复提交延迟
-.显示客户端连接数量
-.显示每次提交间隔
-.修复若干bug

3.此版本刚出来，收费 0.1 sol 永久授权使用，使用时会自动扣费 0.1 sol 


4.客户端可使用旧版本
旧版本链接:
https://hub.nuaa.cf/xiaoniunn/pool-old-client



5.目前仅提供可执行文件版本直接执行命令，即可 ，新版本发布后， 一周内会开源


6.windows执行命令

ore.exe mine --rpc https://node.onekey.so/sol --rpcs https://node.onekey.so/sol --keypair 1.json --keypairs 1.json --priority-fee 6200 

7.linux执行命令

./ore mine --rpc https://node.onekey.so/sol --rpcs https://node.onekey.so/sol --keypair 1.json --keypairs 1.json --priority-fee 6200 














A command line interface for ORE cryptocurrency mining.

## Install

To install the CLI, use [cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html):

```sh
cargo install ore-cli
```

## Build

To build the codebase from scratch, checkout the repo and use cargo to build:

```sh
cargo build --release
```

## Help

You can use the `-h` flag on any command to pull up a help menu with documentation:

```sh
ore -h
```

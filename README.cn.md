# wasm-tools

[English version](./README.md)

 CLI and Rust libraries for low-level manipulation of WebAssembly modules 

![wasm-tools](https://repo.x-cmd.io/wasm-tools.svg?lang=zh)

## 安装

```sh
x install wasm-tools
```

## 代码洞察

合计: **2,024,634** 行代码（覆盖前 5 种语言、共 **2522** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Json | 1,810,064 | 0 | 0 | 748 |
| Rust | 154,737 | 7,535 | 16,943 | 435 |
| WebAssembly | 57,688 | 4,421 | 4,628 | 1308 |
| Toml | 998 | 110 | 174 | 29 |
| CHeader | 313 | 204 | 56 | 2 |

## OpenSSF Scorecard 评分

总评分: **5.4 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **CII-Best-Practices** (0/10) — no effort to earn an OpenSSF best practices badge detected

## 源代码

- **上游仓库**: <https://github.com/bytecodealliance/wasm-tools>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v1.259.0` (2026-09-10)
- **最近提交**: 2026-09-16
- **Release 含资产**: 10 个

## 流行度

- **Star**: 1,790 · **Fork**: 352 · **开放 issue**: 473 · **贡献者**: 197

## 累计统计

- **发布数**: 121 · **已合并 PR**: 2045 · **开放 PR**: 20 · **已关闭 issue**: 365 · **开放 issue**: 108 · **提交数**: 3348

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-18 | 4 | 47 | 4 | 4 | 1 | 43 |
| last60d | 2026-07-19 | 7 | 76 | 7 | 5 | 2 | 74 |
| 90d | 2026-06-19 | 8 | 100 | 7 | 9 | 4 | 101 |
| last180d | 2026-03-21 | 17 | 161 | 8 | 16 | 7 | 166 |
| 360d | 2025-09-22 | 25 | 273 | 9 | 39 | 14 | 276 |
| last720d | 2024-09-27 | 62 | 653 | 13 | 98 | 33 | 620 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [wasm-tools-1.259.0-aarch64-linux.tar.gz](https://github.com/bytecodealliance/wasm-tools/releases/download/v1.259.0/wasm-tools-1.259.0-aarch64-linux.tar.gz) | 5.7 MiB | `native/linux/arm64` |
| [wasm-tools-1.259.0-aarch64-macos.tar.gz](https://github.com/bytecodealliance/wasm-tools/releases/download/v1.259.0/wasm-tools-1.259.0-aarch64-macos.tar.gz) | 4.9 MiB | `native/darwin/arm64` |
| [wasm-tools-1.259.0-aarch64-musl.tar.gz](https://github.com/bytecodealliance/wasm-tools/releases/download/v1.259.0/wasm-tools-1.259.0-aarch64-musl.tar.gz) | 5.7 MiB | `native/linux/arm64/musl` |
| [wasm-tools-1.259.0-aarch64-windows.zip](https://github.com/bytecodealliance/wasm-tools/releases/download/v1.259.0/wasm-tools-1.259.0-aarch64-windows.zip) | 4.1 MiB | `native/win/arm64` |
| [wasm-tools-1.259.0-riscv64-linux.tar.gz](https://github.com/bytecodealliance/wasm-tools/releases/download/v1.259.0/wasm-tools-1.259.0-riscv64-linux.tar.gz) | 6.0 MiB | `native/linux/riscv64` |
| [wasm-tools-1.259.0-wasm32-wasip1.tar.gz](https://github.com/bytecodealliance/wasm-tools/releases/download/v1.259.0/wasm-tools-1.259.0-wasm32-wasip1.tar.gz) | 3.5 MiB | `native/unknown` |
| [wasm-tools-1.259.0-x86_64-linux.tar.gz](https://github.com/bytecodealliance/wasm-tools/releases/download/v1.259.0/wasm-tools-1.259.0-x86_64-linux.tar.gz) | 5.6 MiB | `native/linux/x64` |
| [wasm-tools-1.259.0-x86_64-macos.tar.gz](https://github.com/bytecodealliance/wasm-tools/releases/download/v1.259.0/wasm-tools-1.259.0-x86_64-macos.tar.gz) | 5.3 MiB | `native/darwin/x64` |
| [wasm-tools-1.259.0-x86_64-musl.tar.gz](https://github.com/bytecodealliance/wasm-tools/releases/download/v1.259.0/wasm-tools-1.259.0-x86_64-musl.tar.gz) | 5.9 MiB | `native/linux/x64/musl` |
| [wasm-tools-1.259.0-x86_64-windows.zip](https://github.com/bytecodealliance/wasm-tools/releases/download/v1.259.0/wasm-tools-1.259.0-x86_64-windows.zip) | 4.4 MiB | `native/win/x64` |

## 改进这些数据

wasm-tools 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `wasm-tools` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/wasm-tools.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260917.yml` · 2026-09-17T05:29:25Z._

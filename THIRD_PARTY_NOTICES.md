# Third-Party Open Source Notices

[한국어](#한국어) | [English](#english)

## 한국어

이 문서는 Gitwig 배포와 관련해 사용된 주요 오픈소스 구성요소를 기록합니다. Gitwig 자체는 비오픈소스 무료 배포 소프트웨어이며, 아래 구성요소는 각 프로젝트의 라이선스를 따릅니다.

목록은 `Cargo.lock`과 다음 명령을 기준으로 작성했습니다.

- Runtime: `cargo tree -p git-ffi --edges normal,no-proc-macro`
- Build-time only: `cargo tree -p gitwig-uniffi-bindgen --edges normal`

Apple SDK(`SwiftUI`, `AppKit`, `Security` 등)는 이 목록에 포함하지 않습니다. 이 파일은 오픈소스 구성요소 인벤토리이며, 릴리스 패키지에는 필요 시 각 라이선스 전문 또는 자동 생성된 고지 번들을 함께 포함해야 합니다.

### 직접 의존성

| Component | Version | License | Usage |
| --- | --- | --- | --- |
| `gix` | `0.83.0` | `MIT OR Apache-2.0` | Git repository engine used by Gitwig's Rust core |
| `thiserror` | `2.0.18` | `MIT OR Apache-2.0` | Error type support in Rust crates |
| `uniffi` | `0.31.1` | `MPL-2.0` | Rust-to-Swift FFI binding support |

### Runtime Dependency Inventory

These registry packages are in the `git-ffi` dependency graph with normal runtime edges and proc-macro edges excluded.

| Component | Version | License |
| --- | --- | --- |
| `allocator-api2` | `0.2.21` | `MIT OR Apache-2.0` |
| `anyhow` | `1.0.102` | `MIT OR Apache-2.0` |
| `arc-swap` | `1.9.1` | `MIT OR Apache-2.0` |
| `bitflags` | `2.11.1` | `MIT OR Apache-2.0` |
| `block-buffer` | `0.10.4` | `MIT OR Apache-2.0` |
| `bstr` | `1.12.1` | `MIT OR Apache-2.0` |
| `byteorder` | `1.5.0` | `Unlicense OR MIT` |
| `bytes` | `1.11.1` | `MIT` |
| `camino` | `1.2.2` | `MIT OR Apache-2.0` |
| `cargo-platform` | `0.1.9` | `MIT OR Apache-2.0` |
| `cargo_metadata` | `0.19.2` | `MIT` |
| `cfg-if` | `1.0.4` | `MIT OR Apache-2.0` |
| `clru` | `0.6.3` | `MIT` |
| `cpufeatures` | `0.2.17` | `MIT OR Apache-2.0` |
| `crc32fast` | `1.5.0` | `MIT OR Apache-2.0` |
| `crossbeam-utils` | `0.8.21` | `MIT OR Apache-2.0` |
| `crypto-common` | `0.1.7` | `MIT OR Apache-2.0` |
| `dashmap` | `6.2.1` | `MIT` |
| `digest` | `0.10.7` | `MIT OR Apache-2.0` |
| `encoding_rs` | `0.8.35` | `(Apache-2.0 OR MIT) AND BSD-3-Clause` |
| `equivalent` | `1.0.2` | `Apache-2.0 OR MIT` |
| `errno` | `0.3.14` | `MIT OR Apache-2.0` |
| `faster-hex` | `0.10.0` | `MIT` |
| `fastrand` | `2.4.1` | `Apache-2.0 OR MIT` |
| `filetime` | `0.2.29` | `MIT/Apache-2.0` |
| `fnv` | `1.0.7` | `Apache-2.0 / MIT` |
| `foldhash` | `0.2.0` | `Zlib` |
| `generic-array` | `0.14.7` | `MIT` |
| `getrandom` | `0.4.2` | `MIT OR Apache-2.0` |
| `gix` | `0.83.0` | `MIT OR Apache-2.0` |
| `gix-actor` | `0.41.0` | `MIT OR Apache-2.0` |
| `gix-attributes` | `0.33.0` | `MIT OR Apache-2.0` |
| `gix-bitmap` | `0.3.1` | `MIT OR Apache-2.0` |
| `gix-chunk` | `0.7.1` | `MIT OR Apache-2.0` |
| `gix-command` | `0.9.0` | `MIT OR Apache-2.0` |
| `gix-commitgraph` | `0.37.0` | `MIT OR Apache-2.0` |
| `gix-config` | `0.56.0` | `MIT OR Apache-2.0` |
| `gix-config-value` | `0.18.0` | `MIT OR Apache-2.0` |
| `gix-date` | `0.15.3` | `MIT OR Apache-2.0` |
| `gix-diff` | `0.63.0` | `MIT OR Apache-2.0` |
| `gix-dir` | `0.25.0` | `MIT OR Apache-2.0` |
| `gix-discover` | `0.51.0` | `MIT OR Apache-2.0` |
| `gix-error` | `0.2.3` | `MIT OR Apache-2.0` |
| `gix-features` | `0.48.0` | `MIT OR Apache-2.0` |
| `gix-filter` | `0.30.0` | `MIT OR Apache-2.0` |
| `gix-fs` | `0.21.1` | `MIT OR Apache-2.0` |
| `gix-glob` | `0.26.0` | `MIT OR Apache-2.0` |
| `gix-hash` | `0.25.0` | `MIT OR Apache-2.0` |
| `gix-hashtable` | `0.15.0` | `MIT OR Apache-2.0` |
| `gix-ignore` | `0.21.0` | `MIT OR Apache-2.0` |
| `gix-imara-diff` | `0.2.1` | `Apache-2.0` |
| `gix-index` | `0.51.0` | `MIT OR Apache-2.0` |
| `gix-lock` | `23.0.0` | `MIT OR Apache-2.0` |
| `gix-object` | `0.60.0` | `MIT OR Apache-2.0` |
| `gix-odb` | `0.80.0` | `MIT OR Apache-2.0` |
| `gix-pack` | `0.70.0` | `MIT OR Apache-2.0` |
| `gix-packetline` | `0.21.3` | `MIT OR Apache-2.0` |
| `gix-path` | `0.12.0` | `MIT OR Apache-2.0` |
| `gix-pathspec` | `0.18.0` | `MIT OR Apache-2.0` |
| `gix-protocol` | `0.61.0` | `MIT OR Apache-2.0` |
| `gix-quote` | `0.7.1` | `MIT OR Apache-2.0` |
| `gix-ref` | `0.63.0` | `MIT OR Apache-2.0` |
| `gix-refspec` | `0.41.0` | `MIT OR Apache-2.0` |
| `gix-revision` | `0.45.0` | `MIT OR Apache-2.0` |
| `gix-revwalk` | `0.31.0` | `MIT OR Apache-2.0` |
| `gix-sec` | `0.14.0` | `MIT OR Apache-2.0` |
| `gix-shallow` | `0.12.0` | `MIT OR Apache-2.0` |
| `gix-status` | `0.30.0` | `MIT OR Apache-2.0` |
| `gix-submodule` | `0.30.0` | `MIT OR Apache-2.0` |
| `gix-tempfile` | `23.0.0` | `MIT OR Apache-2.0` |
| `gix-trace` | `0.1.19` | `MIT OR Apache-2.0` |
| `gix-transport` | `0.57.0` | `MIT OR Apache-2.0` |
| `gix-traverse` | `0.57.0` | `MIT OR Apache-2.0` |
| `gix-url` | `0.36.0` | `MIT OR Apache-2.0` |
| `gix-utils` | `0.3.2` | `MIT OR Apache-2.0` |
| `gix-validate` | `0.11.1` | `MIT OR Apache-2.0` |
| `gix-worktree` | `0.52.0` | `MIT OR Apache-2.0` |
| `hash32` | `0.3.1` | `MIT OR Apache-2.0` |
| `hashbrown` | `0.14.5` | `MIT OR Apache-2.0` |
| `hashbrown` | `0.16.1` | `MIT OR Apache-2.0` |
| `hashbrown` | `0.17.1` | `MIT OR Apache-2.0` |
| `heapless` | `0.8.0` | `MIT OR Apache-2.0` |
| `heck` | `0.5.0` | `MIT OR Apache-2.0` |
| `indexmap` | `2.14.0` | `Apache-2.0 OR MIT` |
| `itoa` | `1.0.18` | `MIT OR Apache-2.0` |
| `jiff` | `0.2.25` | `Unlicense OR MIT` |
| `kstring` | `2.0.2` | `MIT OR Apache-2.0` |
| `libc` | `0.2.186` | `MIT OR Apache-2.0` |
| `lock_api` | `0.4.14` | `MIT OR Apache-2.0` |
| `memchr` | `2.8.0` | `Unlicense OR MIT` |
| `memmap2` | `0.9.10` | `MIT OR Apache-2.0` |
| `nonempty` | `0.12.0` | `MIT` |
| `once_cell` | `1.21.4` | `MIT OR Apache-2.0` |
| `parking_lot` | `0.12.5` | `MIT OR Apache-2.0` |
| `parking_lot_core` | `0.9.12` | `MIT OR Apache-2.0` |
| `percent-encoding` | `2.3.2` | `MIT OR Apache-2.0` |
| `prodash` | `31.0.0` | `MIT` |
| `regex-automata` | `0.4.14` | `MIT OR Apache-2.0` |
| `rustix` | `1.1.4` | `Apache-2.0 WITH LLVM-exception OR Apache-2.0 OR MIT` |
| `same-file` | `1.0.6` | `Unlicense/MIT` |
| `scopeguard` | `1.2.0` | `MIT OR Apache-2.0` |
| `semver` | `1.0.28` | `MIT OR Apache-2.0` |
| `serde` | `1.0.228` | `MIT OR Apache-2.0` |
| `serde_core` | `1.0.228` | `MIT OR Apache-2.0` |
| `serde_json` | `1.0.150` | `MIT OR Apache-2.0` |
| `sha1` | `0.10.6` | `MIT OR Apache-2.0` |
| `sha1-checked` | `0.10.0` | `MIT OR Apache-2.0` |
| `shell-words` | `1.1.1` | `MIT/Apache-2.0` |
| `smallvec` | `1.15.1` | `MIT OR Apache-2.0` |
| `stable_deref_trait` | `1.2.1` | `MIT OR Apache-2.0` |
| `static_assertions` | `1.1.0` | `MIT OR Apache-2.0` |
| `tempfile` | `3.27.0` | `MIT OR Apache-2.0` |
| `thiserror` | `2.0.18` | `MIT OR Apache-2.0` |
| `tinyvec` | `1.11.0` | `Zlib OR Apache-2.0 OR MIT` |
| `tinyvec_macros` | `0.1.1` | `MIT OR Apache-2.0 OR Zlib` |
| `typenum` | `1.20.0` | `MIT OR Apache-2.0` |
| `unicode-bom` | `2.0.3` | `Apache-2.0` |
| `unicode-normalization` | `0.1.25` | `MIT OR Apache-2.0` |
| `uniffi` | `0.31.1` | `MPL-2.0` |
| `uniffi_core` | `0.31.1` | `MPL-2.0` |
| `uniffi_pipeline` | `0.31.1` | `MPL-2.0` |
| `walkdir` | `2.5.0` | `Unlicense/MIT` |
| `zlib-rs` | `0.6.3` | `Zlib` |
| `zmij` | `1.0.21` | `MIT` |

### Build-Time Only Dependency Inventory

These packages are used by the binding generator or compile-time tooling and are not intended to be bundled as runtime app components.

| Component | Version | License |
| --- | --- | --- |
| `anstyle` | `1.0.14` | `MIT OR Apache-2.0` |
| `askama` | `0.14.0` | `MIT OR Apache-2.0` |
| `askama_derive` | `0.14.0` | `MIT OR Apache-2.0` |
| `askama_parser` | `0.14.0` | `MIT OR Apache-2.0` |
| `basic-toml` | `0.1.10` | `MIT OR Apache-2.0` |
| `clap` | `4.6.1` | `MIT OR Apache-2.0` |
| `clap_builder` | `4.6.0` | `MIT OR Apache-2.0` |
| `clap_derive` | `4.6.1` | `MIT OR Apache-2.0` |
| `clap_lex` | `1.1.0` | `MIT OR Apache-2.0` |
| `fs-err` | `2.11.0` | `MIT/Apache-2.0` |
| `glob` | `0.3.3` | `MIT OR Apache-2.0` |
| `goblin` | `0.8.2` | `MIT` |
| `log` | `0.4.30` | `MIT OR Apache-2.0` |
| `minimal-lexical` | `0.2.1` | `MIT/Apache-2.0` |
| `nom` | `7.1.3` | `MIT` |
| `plain` | `0.2.3` | `MIT/Apache-2.0` |
| `proc-macro2` | `1.0.106` | `MIT OR Apache-2.0` |
| `quote` | `1.0.45` | `MIT OR Apache-2.0` |
| `rustc-hash` | `2.1.2` | `Apache-2.0 OR MIT` |
| `scroll` | `0.12.0` | `MIT` |
| `scroll_derive` | `0.12.1` | `MIT` |
| `serde_derive` | `1.0.228` | `MIT OR Apache-2.0` |
| `serde_spanned` | `1.1.1` | `MIT OR Apache-2.0` |
| `siphasher` | `1.0.3` | `MIT/Apache-2.0` |
| `smawk` | `0.3.2` | `MIT` |
| `strsim` | `0.11.1` | `MIT` |
| `syn` | `2.0.117` | `MIT OR Apache-2.0` |
| `textwrap` | `0.16.2` | `MIT` |
| `thiserror-impl` | `2.0.18` | `MIT OR Apache-2.0` |
| `toml` | `0.9.12+spec-1.1.0` | `MIT OR Apache-2.0` |
| `toml_datetime` | `0.7.5+spec-1.1.0` | `MIT OR Apache-2.0` |
| `toml_parser` | `1.1.2+spec-1.1.0` | `MIT OR Apache-2.0` |
| `toml_writer` | `1.1.1+spec-1.1.0` | `MIT OR Apache-2.0` |
| `unicode-ident` | `1.0.24` | `(MIT OR Apache-2.0) AND Unicode-3.0` |
| `uniffi_bindgen` | `0.31.1` | `MPL-2.0` |
| `uniffi_internal_macros` | `0.31.1` | `MPL-2.0` |
| `uniffi_macros` | `0.31.1` | `MPL-2.0` |
| `uniffi_meta` | `0.31.1` | `MPL-2.0` |
| `uniffi_udl` | `0.31.1` | `MPL-2.0` |
| `weedle2` | `5.0.0` | `MIT` |
| `winnow` | `0.7.15` | `MIT` |
| `winnow` | `1.0.3` | `MIT` |

## English

This document records the main open source components used by Gitwig distribution. Gitwig itself is proprietary freeware; the components listed above remain governed by their own project licenses.

The inventory is generated from `Cargo.lock` using the runtime and build-time commands listed in the Korean section. Apple SDK components such as `SwiftUI`, `AppKit`, and `Security` are not included. This file is an open source component inventory; release packages should include complete license texts or generated notice bundles when required by the applicable licenses.

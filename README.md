# Awesome Rust CLI Tools

> A curated list of production-ready command-line utilities built with Rust. Fast, safe, memory-efficient, and single-binary distributable.

---

### 📊 Repository Summary
| Metric | Value |
|--------|-------|
| **Total Tools** | 73+ |
| **Categories** | 12 |
| **Star Coverage** | 10+ stars |
| **License** | MIT |

---

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub Stars](https://img.shields.io/github/stars/Mayne-X/awesome-rust-cli-tools)](https://github.com/Mayne-X/awesome-rust-cli-tools/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/Mayne-X/awesome-rust-cli-tools)](https://github.com/Mayne-X/awesome-rust-cli-tools/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Why Rust for CLI Tools?

Rust offers unique advantages for command-line applications:
- **⚡ Performance** - Often matches or exceeds C/C++ speeds
- **🛡️ Safety** - Zero null pointer dereferences, buffer overflows
- **📦 Deployability** - Single static binary, no runtime dependencies
- **🌐 Portability** - Compile once, run anywhere (Windows/macOS/Linux)
- **🔧 Ergonomics** - Excellent error messages, cargo ecosystem

## Table of Contents

- [File & System Operations](#file--system-operations)
- [Development Tools](#development-tools)
- [Git & Version Control](#git--version-control)
- [Text Processing](#text-processing)
- [Networking & Web](#networking--web)
- [Data & Databases](#data--databases)

## File & System Operations

Tools for file management, searching, and system interactions.

| Tool | Description | Stars | Last Updated |
|------|-------------|-------|--------------|
| [bat](https://github.com/sharkdp/bat) | A cat(1) clone with syntax highlighting | 43,200 | 2026-06-01 |
| [delta](https://github.com/dandavison/delta) | A syntax-highlighting pager for git, diff, and grep | 6,671 | 2026-05-12 |
| [dua-cli](https://github.com/Byron/dua-cli) | View disk space usage and delete unwanted data, fast | 5,200 | 2026-04-10 |
| [dust](https://github.com/bootandy/dust) | A more intuitive version of du in rust | 11,800 | 2026-06-05 |
| [eza](https://github.com/eza-community/eza) | A modern, user-friendly replacement for ls | 5,752 | 2026-06-09 |
| [fd](https://github.com/sharkdp/fd) | A simple, fast and user-friendly alternative to find | 35,400 | 2026-05-20 |
| [gron](https://github.com/tomwright/gron) | Flatten and inspect JSON into a human-readable format | 4,824 | 2025-11-16 |
| [lsd](https://github.com/Pilu58/lsd) | Lightweight and full-featured file manager | 3,042 | 2025-10-24 |
| [nnn](https://github.com/jarun/nnn) | The unorthodox terminal file manager | 4,548 | 2026-01-15 |
| [ripgrep](https://github.com/BurntSushi/ripgrep) | A command-line utility to search text across all files | 1,836 | 2025-12-08 |

## Development Tools

Build systems, linters, formatters, and debugging utilities.

| Tool | Description | Stars | Last Updated |
|------|-------------|-------|--------------|
| [cargo-expand](https://github.com/danielhenrycx/cargo-expand) | Expands your build script and dependencies to show you what Cargo is actually compiling | 2,832 | 2026-02-08 |
| [cargo-watch](https://github.com/watchex/notify) | Watch your Cargo projects and run commands when files change | 8,610 | 2026-06-05 |
| [cargo-nextest](https://github.com/stretchr-rs/nextest) | A next-generation test runner for Rust | 2,987 | 2026-05-19 |
| [cargo-make](https://github.com/sagieguy/cargo-make) | Very opinionated task runner for Rust projects | 2,937 | 2026-03-12 |
| [cargo-edit](https://github.com/matze93/cargo-edit) | Edit Cargo.lock and workspace Cargo.toml interactively | 2,010 | 2026-02-15 |
| [rolldown](https://github.com/rolldown/rolldown) | Extremely fast Rust bundler | 3,492 | 2026-05-23 |
| [rustup](https://github.com/rust-lang/rustup) | Manage multiple Rust installations on one system | 15,889 | 2026-06-01 |

## Git & Version Control

Git extensions, repository management, diff tools, and history visualization tools.

| Tool | Description | Stars | Last Updated |
|------|-------------|-------|--------------|
| [gitui](https://github.com/extrawurst/gitui) | Blazing fast terminal-ui for git | 17,590 | 2026-06-10 |
| [git-cliff](https://github.com/orhun/git-cliff) | A high customizable Changelog Generator | 7,715 | 2026-06-08 |
| [tig](https://github.com/jonas/tig) | Text-mode interface for git | 14,123 | 2025-10-23 |
| [lazygit](https://github.com/jesseduffield/lazygit) | Simple terminal UI for git commands | 32,841 | 2026-06-12 |
| [gh-dash](https://github.com/dlvhdr/gh-dash) | A rich terminal UI for GitHub that doesn't break your flow | 1,123 | 2026-02-28 |

## Text Processing

Text manipulation tools, formatters, processors, and data extraction utilities.

| Tool | Description | Stars | Last Updated |
|------|-------------|-------|--------------|
| [jq](https://github.com/stedolan/jq) | Command-line JSON processor | 43,104 | 2026-02-10 |
| [yq](https://github.com/mikefarah/yq) | YAML processor similar to jq but for processing YAML | 10,502 | 2026-04-19 |

## Networking & Web

Network tools, HTTP clients, API interfaces, and network diagnostics.

| Tool | Description | Stars | Last Updated |
|------|-------------|-------|--------------|
| [httpie](https://github.com/httpie/httpie) | User-friendly curl alternative for HTTP requests | 41,643 | 2025-12-01 |
| [curlie](https://github.com/rs/curlie) | Curlie is a curl frontend with the ease of use of HTTPie | 12,764 | 2025-11-08 |
| [curl](https://github.com/curl/curl) | Command line tool for URL retrieval | 5,891 | 2026-06-07 |

## Data & Databases

Database clients, query tools, data formats processors, and database management utilities.

| Tool | Description | Stars | Last Updated |
|------|-------------|-------|--------------|
| [sqlite](https://github.com/sqlite/sqlite) | SQL database engine | 284,636 | 2026-06-15 |
| [pgcli](https://github.com/pgcli/pgcli) | PostgreSQL client | 7,671 | 2026-03-24 |
| [mysqlclient](https://github.com/farribly/mysqlclient) | MySQL client | 11,569 | 2025-12-17 |
| [duckdb](https://github.com/duckdb/duckdb) | Embedded analytics database for Rust | 7,854 | 2026-06-03 |

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT License - see [LICENSE](LICENSE) file.

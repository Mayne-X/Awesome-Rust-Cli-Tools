# Awesome Rust CLI Tools

> A curated list of production-ready command-line utilities built with Rust. Fast, safe, memory-efficient, and single-binary distributable.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub Stars](https://img.shields.io/github/stars/Mayne-X/awesome-rust-cli-tools)](https://github.com/Mayne-X/awesome-rust-cli-tools/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/Mayne-X/awesome-rust-cli-tools)](https://github.com/Mayne-X/awesome-rust-cli-tools/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub last commit](https://img.shields.io/github/last-commit/Mayne-X/awesome-rust-cli-tools)](https://github.com/Mayne-X/awesome-rust-cli-tools/commits/main)
[![GitHub issues](https://img.shields.io/github/issues/Mayne-X/awesome-rust-cli-tools)](https://github.com/Mayne-X/awesome-rust-cli-tools/issues)
[![GitHub PRs](https://img.shields.io/github/issues-pr/Mayne-X/awesome-rust-cli-tools)](https://github.com/Mayne-X/awesome-rust-cli-tools/pulls)

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
- [System Administration](#system-administration)
- [Security & Privacy](#security--privacy)
- [AI & Machine Learning](#ai--machine-learning)
- [Media & Graphics](#media--graphics)
- [Testing & Quality Assurance](#testing--quality-assurance)
- [Productivity & Utilities](#productivity--utilities)

## File & System Operations

Tools for file management, searching, and system interactions. Performance and safety are top priorities.

| Tool | Description | Stars | Last Updated |
|------|-------------|-------|--------------|
| [delta](https://github.com/dandavison/delta) | A syntax-highlighting pager that supports multiple languages and outputs to terminals and web browsers | ⭐ 6,671 | 2026-05-12 |
| [eza](https://github.com/eza-community/eza) | A modern, user-friendly replacement for ls | ⭐ 5,752 | 2026-06-09 |
| [gifh](https://github.com/xhuehi/gifh) | Converts GIF to ASCII art using `cacaos` library | ⭐ 336 | 2026-03-21 |
| [gron](https://github.com/tomwright/gron) | Flatten and inspect JSON/

[Gron](https://github.com/tomwright/gron) transforms JSON into a human-readable format
within your terminal window.| ⭐ 4,824 | 2025-11-16 |
| [hl](https://github.com/hl255/HL) | Highlighter / syntax highlighter for the terminal. Supports over 200 file types | ⭐ 1,443 | 2026-03-26 |
| [lsd](https://github.com/Pilu58/lsd) | Lightweight and full-featured file manager | ⭐ 3,042 | 2025-10-24 |
| [nnn](https://github.com/jarun/nnn) | The unorthodox terminal file manager | ⭐ 4,548 | 2026-01-15 |
| [ripgrep](https://github.com/BurntSushi/ripgrep) | A command-line utility to search text across all files in a directory | ⭐ 1,836 | 2025-12-08 |
| [rug](https://github.com/mitchellh/rug) | A more useful port of the Unix `du` command (disk usage)

[Rug](https://github.com/mitchellh/rug) provides more detailed disk usage reporting across directories| ⭐ 484 | 2026-02-19 |
| [saw](https://github.com/reatape/saw) | A command-line tool for watching log file changes | ⭐ 454 | 2026-03-05 |
| [toilet](https://github.com/ncolloff/toilet) | A cross-platform fun way to visualize a file | ⭐ 4,570 | 2025-09-13 |
| [tspin](https://github.com/john-cdavis/tspin) | A terminal spinner for your CLI | ⭐ 635 | 2026-05-29 |

## Development Tools

Build systems, linters, formatters, and debugging utilities that leverage Rust's strengths.

| Tool | Description | Stars | Last Updated |
|------|-------------|-------|--------------|
| [cargo-expand](https://github.com/danielhenrycx/cargo-expand) | Expands your build script and dependencies to show you what Cargo is actually compiling | ⭐ 2,832 | 2026-02-08 |
| [cargo watch](https://github.com/watchex/notify) | Watch your Cargo projects and run commands when files change | ⭐ 8,610 | 2026-06-05 |
| [cargo-nextest](https://github.com/stretchr-rs/nextest) | A next-generation test runner for Rust | ⭐ 2,987 | 2026-05-19 |
| [cargo ran](https://github.com/rust-lang/cargo-run) | Run the build command and keep the resulting executable in PATH without cleaning up | ⭐ 2,094 | 2026-01-17 |
| [cargo-make](https://github.com/sagieguy/cargo-make) | Very opinionated task runner for Rust projects | ⭐ 2,937 | 2026-03-12 |
| [cargo-edit](https://github.com/matze93/cargo-edit) | Edit Cargo.lock and workspace Cargo.toml interactively | ⭐ 2,010 | 2026-02-15 |
| [du-micros](https://github.com/deliusen/du-micros) | A collection of small 'du' (disk usage) tools | ⭐ 467 | 2026-03-24 |
| [madder](https://github.com/creacy/madder) | A lightweight fat installer for command-line applications | ⭐ 577 | 2026-04-30 |
| [rolldown](https://github.com/rolldown/rolldown) | Extremely fast Rust bundler | ⭐ 3,492 | 2026-05-23 |
| [rustup](https://github.com/rust-lang/rustup) | Manage multiple Rust installations on one system | ⭐ 15,889 | 2026-06-01 |
| [swiff](https://github.com/EbobSwiff/swiff) | SwiftBinary - high performance CLI formatter/wrapper for Rust (wasm)-based Swift binaries | ⭐ 94 | 2025-11-28 |
| [vulcansync](https://github.com/DenisToznyi/vulcansync) | Sync imported generated docs from workspace and workspace | ⭐ 425 | 2026-04-11 |

## Git & Version Control

Git extensions, repository management, diff tools, and history visualization tools.

| Tool | Description | Stars | Last Updated |
|------|-------------|-------|--------------|
| [gitui](https://github.com/extrawurst/gitui) | Blazing fast terminal-ui for git | ⭐ 17,590 | 2026-06-10 |
| [git-cliff](https://github.com/orhun/git-cliff) | A high customizable Changelog Generator that follows Conventional Commit specifications | ⭐ 7,715 | 2026-06-08 |
| [mr](https://github.com/a4m4/mr) | Manage multiple git repositories (rails integration)

[MR](https://github.com/a4m4/mr) allows you to manage multiple git repositories (rails integration) interactively| ⭐ 2,566 | 2026-04-17 |
| [ifshenv](https://github.com/zxdavb/ifshenv) | Use IFSHENVS under git bash and cmd as that

[IFS] environment, a better shell for programming, you can edit files easily and work on tools written in bats, Python or Go| ⭐ 3,759 | 2026-05-08 |
| [tig](https://github.com/jonas/tig) | Text-mode interface for git | ⭐ 14,123 | 2025-10-23 |
| [lazygit](https://github.com/jesseduffield/lazygit) | Simple terminal UI for git commands | ⭐ 32,841 | 2026-06-12 |
| [gh-dash](https://github.com/dlvhdr/gh-dash) | A rich terminal UI for GitHub that doesn't break your flow | ⭐ 1,123 | 2026-02-28 |
| [commit](https://github.com/act1218/commit) | Interactive commit message generator for git | ⭐ 1,409 | 2026-04-05 |
| [git-recover](https://github.com/inancogit/git-recover) | An interactive script to help you restore/stash files with the `git checkout -- <path>` command | ⭐ 789 | 2025-11-30 |
| [gitpulse](https://github.com/mos6essb/gitpulse) | GitPulse: terminal-based git viewer for activity | ⭐ 184 | 2026-05-14 |
| [ghr](https://github.com/cli/cli) | GitHub CLI (general, but CLI). Use GitHub from the terminal | ⭐ 29,760 | 2026-06-08 |
| [hurl](https://github.com/vindicia/hurl) | Hurl - a request builder and HTTP client tests tool | ⭐ 885 | 2026-03-19 |

## Text Processing

Text manipulation tools, formatters, processors, and data extraction utilities.

| Tool | Description | Stars | Last Updated |
|------|-------------|-------|--------------|
| [jq](https://github.com/stedolan/jq) | Command-line JSON processor | ⭐ 43,104 | 2026-02-10 |
| [yq](https://github.com/mikefarah/yq) | YAML processor similar to jq but for processing YAML | ⭐ 10,502 | 2026-04-19 |
| [df](https://github.com/sharkd/df) | Show file types | ⭐ 5,690 | 2026-01-28 |
| [last](https://github.com/sunyalpem/content-of-tweet-handles) | Go client for Last.fm API | ⭐ 64 | 2026-03-08 |
| [tx](https://github.com/torrin84/tx) | Turn commands output into linear file content | ⭐ 214 | 2026-02-15 |
| [normal](https://github.com/bcicen/normal) | Pretty, normalized column output | ⭐ 2,093 | 2025-11-17 |
| [glances](https://github.com/nicolargo/glances) | A system monitor written in Python (also has rust CLI)

[Glances](https://github.com/nicolargo/glances) of course also provides a Python version but the Rust CLI is available in the repository| ⭐ 19,215 | 2026-06-14 |
| [fugue](https://github.com/sayanarijit/fugue) | General purpose commands and APIs for JavaScript (Node.js) and Wasi runtime | ⭐ 872 | 2026-04-26 |
| [tailarch](https://github.com/ankitgupta0507/tailarch) | Cross platform tail command, works like 'tail -f' having more functionalities | ⭐ 84 | 2026-05-03 |

## Networking & Web

Network tools, HTTP clients, API interfaces, and network diagnostics.

| Tool | Description | Stars | Last Updated |
|------|-------------|-------|--------------|
| [httpie](https://github.com/httpie/httpie) | User-friendly curl alternative for HTTP requests | ⭐ 41,643 | 2025-12-01 |
| [curlie](https://github.com/rs/curlie) | Curlie is a curl frontend with the ease of use of HTTPie | ⭐ 12,764 | 2025-11-08 |
| [curl](https://github.com/curl/curl) | Command line tool for URL retrieval | ⭐ 5,891 | 2026-06-07 |
| [bat](https://github.com/sharkdp/bat) | Con.cat a cat, but much better | ⭐ 16,560 | 2026-05-23 |
| [nyc](https://github.com/istanbuljs/nyc) | Istanbul's JavaScript code coverage tool | ⭐ 2,363 | 2026-06-02 |
| [postman](https://github.com/postmanlabs/postman-app-support) | Legacy Postman collection support for CLI

[Postman](https://github.com/postmanlabs/postman-app-support) provides legacy collection support for CLI via bridge| ⭐ 485 | 2025-10-15 |
| [postman-cli](https://github.com/grubersjoe/postman-cli) | Postman CLI | ⭐ 1,058 | 2026-04-28 |
| [http-prompt](https://github.com/eliangcs/http-prompt) | Interactive HTTP client featuring autocomplete and syntax highlighting | ⭐ 7,568 | 2026-02-21 |

## Data & Databases

Database clients, query tools, data formats processors, and database management utilities.

| Tool | Description | Stars | Last Updated |
|------|-------------|-------|--------------|
| [sqlite](https://github.com/sqlite/sqlite) | SQL database engine | ⭐ 284,636 | 2026-06-15 |
| [pgcli](https://github.com/pgcli/pgcli) | PostgreSQL client | ⭐ 7,671 | 2026-03-24 |
| [mysqlclient](https://github.com/farribly/mysqlclient) | MySQL client | ⭐ 11,569 | 2025-12-17 |
| [peewee](https://github.com/peewee/peewee) | Minimalistic database tooling (Rust-based client wrapper)

[Peewee](https://github.com/peewee/peewee) is a database toolkit for Python, but they have Rust packages| ⭐ 12,123 | 2026-02-28 |
| [duckdb](https://github.com/duckdb/duckdb) | Embedded analytics database for Rust | ⭐ 7,854 | 2026-06-03 |
| [clickhouse-rs](https://github.com/clickhouse-rs/clickhouse-rs) | ClickHouse client for Rust | ⭐ 492 | 2026-05-15 |
| [mongodb-rust-driver](https://github.com/mongodb/mongo-rust-driver) | MongoDB driver with Rust | ⭐ 635 | 2026-04-09 |

<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="https://github.com/kud1ing/awesome-rust">https://github.com/kud1ing/awesome-rust</a> with ranks
</p>
---
# Awesome Rust

A curated list of Rust code and resources, inspired by other awesome lists.

If you want to contribute, please read [this](https://github.com/kud1ing/awesome-rust/blob/master/CONTRIBUTING.md).

## Table of Contents

- [Applications written in Rust](#applications-written-in-rust)
- [Development Tools](#development-tools)
  - [Build system](#build-system)
  - [Debugging](#debugging)
  - [Deployment](#deployment)
  - [Embedded](#embedded)
  - [FFI](#ffi)
  - [IDEs](#ides)
  - [Profiling](#profiling)
  - [Testing](#testing)
- [Libraries](#libraries)
  - [Astronomy](#astronomy)
  - [Asynchronous](#asynchronous)
  - [Audio](#audio)
  - [Authentication](#authentication)
  - [Bioinformatics](#bioinformatics)
  - [Caching](#caching)
  - [Cloud](#cloud)
  - [Command-line argument parsing](#command-line-argument-parsing)
  - [Command-line interface](#command-line-interface)
  - [Compression](#compression)
  - [Computation](#computation)
  - [Concurrency](#concurrency)
  - [Configuration](#configuration)
  - [Cryptography](#cryptography)
  - [Database](#database)
  - [Data structures](#data-structures)
  - [Date and time](#date-and-time)
  - [Distributed Systems](#distributed-systems)
  - [Email](#email)
  - [Encoding](#encoding)
  - [Filesystem](#filesystem)
  - [Game development](#game-development)
  - [Geospatial](#geospatial)
  - [Graphics](#graphics)
  - [Graph processing](#graph-processing)
  - [GUI](#gui)
  - [Image processing](#image-processing)
  - [Logging](#logging)
  - [Machine learning](#machine-learning)
  - [Markup language](#markup-language)
  - [Mobile](#mobile)
  - [Network programming](#network-programming)
  - [Parser](#parser)
  - [Platform specific](#platform-specific)
  - [Scripting](#scripting)
  - [Template engine](#template-engine)
  - [Text processing](#text-processing)
  - [Text search](#text-search)
  - [Virtualization](#virtualization)
  - [Web programming](#web-programming)
- [Resources](#resources)
- [License](#license)


## Applications written in Rust

See also [Friends of Rust](https://www.rust-lang.org/friends.html) (organizations running Rust in production).

* [andschwa/rust-genetic-algorithm ★19](https://github.com/andschwa/rust-genetic-algorithm) — a genetic algorithm for academic benchmark problems [<img src="https://travis-ci.org/andschwa/rust-genetic-algorithm.svg?branch=master">](https://travis-ci.org/andschwa/rust-genetic-algorithm)
* [azerupi/mdBook ★484](https://github.com/azerupi/mdBook) — a command line utility to create books from markdown files [<img src="https://travis-ci.org/azerupi/mdBook.svg?branch=master">](https://travis-ci.org/azerupi/mdBook)
* [bluejekyll/trust-dns ★482](https://github.com/bluejekyll/trust-dns) — a DNS-server [<img src="https://travis-ci.org/bluejekyll/trust-dns.svg?branch=master">](https://travis-ci.org/bluejekyll/trust-dns)
* [ivanceras/curtain ★129](https://github.com/ivanceras/curtain) — a database administration tool for postgresql [<img src="https://api.travis-ci.org/ivanceras/curtain.svg">](https://travis-ci.org/ivanceras/curtain)
* [darrint/device-blocker ★9](https://github.com/darrint/device-blocker) — Limit screen time to children's various mobile devices by blocking internet access on the family Wifi router.
* [dlecan/generic-dns-update ★2](https://github.com/dlecan/generic-dns-update) — a tool to update DNS zonefiles with your IP address [<img src="https://travis-ci.org/dlecan/generic-dns-update.svg?branch=master">](https://travis-ci.org/dlecan/generic-dns-update)
* [Factotum ★74](https://github.com/snowplow/factotum) — [A system to programmatically run data pipelines](http://snowplowanalytics.com/blog/2016/04/09/introducing-factotum-data-pipeline-runner/) [<img src="https://travis-ci.org/snowplow/factotum.svg?branch=master">](https://travis-ci.org/snowplow/factotum)
* [Fractalide ★285](https://github.com/fractalide/fractalide) — Simple Rust Microservices
* [imjacobclark/Herd ★63](https://github.com/imjacobclark/Herd) — an experimental HTTP load testing application
* [intecture/api ★4](https://github.com/intecture/api) — an API-driven server management and configuration tool [<img src="https://travis-ci.org/intecture/api.svg?branch=master">](https://travis-ci.org/intecture/api)
* [jedisct1/flowgger ★215](https://github.com/jedisct1/flowgger) — a fast, simple and lightweight data collector
* [jwilm/alacritty ★5712](https://github.com/jwilm/alacritty) — a cross-platform, GPU enhanced terminal emulator
* [kbknapp/docli ★25 ⏳1Y](https://github.com/kbknapp/docli-rs) — a command line utility for managing DigitalOcean infrastructure [<img src="https://travis-ci.org/kbknapp/docli-rs.svg?branch=master">](https://travis-ci.org/kbknapp/docli-rs)
* [MaidSafe](http://maidsafe.net/) — a decentralized platform.
* [notty ★1432](https://github.com/withoutboats/notty) — A new kind of terminal
* [qmx/limonite ★23](https://github.com/qmx/limonite) — static blog/website generator [<img src="https://travis-ci.org/qmx/limonite.svg?branch=master">](https://travis-ci.org/qmx/limonite)
* [Sandstorm Collections App ★11](https://github.com/sandstorm-io/collections-app)
* [Servo ★9321](https://github.com/servo/servo) — a prototype web browser engine
* [Parity ★1000](https://github.com/paritytech/parity) — Fast, light, and robust Ethereum implementation [![build status](https://gitlab.ethcore.io/parity/parity/badges/master/build.svg)](https://gitlab.ethcore.io/parity/parity/commits/master)
* [parity-bitcoin ★154](https://github.com/paritytech/parity-bitcoin) - The Parity Bitcoin client [<img src="https://travis-ci.com/paritytech/parity-bitcoin.svg?token=DMFvZu71iaTbUYx9UypX&branch=master">](https://travis-ci.com/paritytech/parity-bitcoin)

* **Audio**
  * [indiscipline/zrtstr](https://github.com/indiscipline/zrtstr) — a command line utility for checking if stereo wav files are faux-stereo (i.e. have identical channels) and converting such files to mono. [<img src="https://travis-ci.org/indiscipline/zrtstr.svg?branch=master">](https://travis-ci.org/indiscipline/zrtstr)
* **Database**
  * [pingcap/tikv ★1767](https://github.com/pingcap/tikv) — a distributed KV database in Rust [<img src="https://travis-ci.org/pingcap/tikv.svg?branch=master">](https://travis-ci.org/pingcap/tikv)
  * [seppo0010/rsedis ★1032](https://github.com/seppo0010/rsedis) — a Redis reimplementation in Rust [<img src="https://travis-ci.org/seppo0010/rsedis.svg?branch=master">](https://travis-ci.org/seppo0010/rsedis)
  * [PumpkinDB/PumpkinDB ★670](https://github.com/PumpkinDB/PumpkinDB) — an event sourcing database engine [<img src="https://travis-ci.org/PumpkinDB/PumpkinDB.svg?branch=master">](https://travis-ci.org/PumpkinDB/PumpkinDB)
* **Emulators** [[emulator](https://crates.io/keywords/emulator)]
  * Commodore 64
    * [kondrak/rust64 ★63 ⏳1Y](https://github.com/kondrak/rust64) — [<img src="https://travis-ci.org/kondrak/rust64.svg?branch=master">](https://travis-ci.org/kondrak/rust64)
  * Gameboy
    * [Gekkio/mooneye-gb ★152](https://github.com/Gekkio/mooneye-gb) — [<img src="https://travis-ci.org/Gekkio/mooneye-gb.svg?branch=master">](https://travis-ci.org/Gekkio/mooneye-gb)
    * [mvdnes/rboy ★42](https://github.com/mvdnes/rboy) — [<img src="https://travis-ci.org/mvdnes/rboy.svg?branch=master">](https://travis-ci.org/mvdnes/rboy)
    * [NivenT/RGB ★5](https://github.com/nivent/RGB) — [<img src="https://travis-ci.org/NivenT/RGB.svg?branch=master">](https://travis-ci.org/NivenT/RGB)
  * NES
    * [iamsix/oxidenes ★22](https://github.com/iamsix/oxidenes) — [<img src="https://travis-ci.org/iamsix/oxidenes.svg?branch=master">](https://travis-ci.org/iamsix/oxidenes)
    * [koute/pinky ★124](https://github.com/koute/pinky) — [<img src="https://travis-ci.org/koute/pinky.svg?branch=master">](https://travis-ci.org/koute/pinky)
    * [pcwalton/sprocketnes ★524](https://github.com/pcwalton/sprocketnes) — [<img src="https://travis-ci.org/pcwalton/sprocketnes.svg?branch=master">](https://travis-ci.org/pcwalton/sprocketnes)
  * Playstation
    * [simias/rustation ★299](https://github.com/simias/rustation) — [<img src="https://travis-ci.org/simias/rustation.svg?branch=master">](https://travis-ci.org/simias/rustation)
  * ZX Spectrum
    * [pacmancoder/rustzx ★26](https://github.com/pacmancoder/rustzx) — [<img src="https://travis-ci.org/pacmancoder/rustzx.svg?branch=master">](https://travis-ci.org/pacmancoder/rustzx)
  * Virtual Boy
    * [emu-rs/rustual-boy ★66](https://github.com/emu-rs/rustual-boy) — [<img src="https://travis-ci.org/emu-rs/rustual-boy.svg?branch=master">](https://travis-ci.org/emu-rs/rustual-boy)
  * Emulator Development tools
    * SNES
      * [ioncodes/snesutilities ★1](https://github.com/ioncodes/snesutilities) — ROM analyser/extractor
* **Games**, see also [Games Made With Piston](https://github.com/PistonDevelopers/piston/wiki/Games-Made-With-Piston).
  * [lifthrasiir/angolmois-rust ★70 ⏳1Y](https://github.com/lifthrasiir/angolmois-rust) — a minimalistic music video game which supports the BMS format [<img src="https://travis-ci.org/lifthrasiir/angolmois-rust.svg?branch=master">](https://travis-ci.org/lifthrasiir/angolmois-rust)
  * [swatteau/sokoban-rs ★67](https://github.com/swatteau/sokoban-rs) — a Sokoban implementation
  * [Zone of Control ★233](https://github.com/ozkriff/zoc) — a turn-based hexagonal strategy game [<img src="https://travis-ci.org/ozkriff/zoc.svg?branch=master">](https://travis-ci.org/ozkriff/zoc)
  * [rhex ★66](https://github.com/dpc/rhex) — hexagonal ascii roguelike
  * [citybound ★627](https://github.com/citybound/citybound) — The city sim you deserve
* **Graphics**
  * [ivanceras/svgbobrus ★249](https://github.com/ivanceras/svgbobrus) — converts ASCII diagrams into SVG graphics [<img src="https://api.travis-ci.org/ivanceras/svgbobrus.svg">](https://travis-ci.org/ivanceras/svgbobrus)
  * [RazrFalcon/svgcleaner ★400](https://github.com/RazrFalcon/svgcleaner) — tidies SVG graphics
  * [Twinklebear/tray_rust ★207](https://github.com/Twinklebear/tray_rust) — a ray tracer [<img src="https://api.travis-ci.org/Twinklebear/tray_rust.svg">](https://travis-ci.org/Twinklebear/tray_rust)
* **Operating systems**, see also [A comparison of operating systems written in Rust ★123](https://github.com/flosse/rust-os-comparison)
  * [redox-os/redox ★6630](https://github.com/redox-os/redox) — [<img   src="https://travis-ci.org/redox-os/redox.svg?branch=master">](https://travis-ci.org/redox-os/redox)
  * [thepowersgang/rust_os ★195](https://github.com/thepowersgang/rust_os) — [<img src="https://travis-ci.org/thepowersgang/rust_os.svg?branch=master">](https://travis-ci.org/thepowersgang/rust_os)
* **System tools**
  * [Aaronepower/tokei ★262](https://github.com/Aaronepower/tokei) — counts the lines of code [<img src="https://img.shields.io/travis/Aaronepower/tokei.svg">](https://travis-ci.org/Aaronepower/tokei)
  * [buster/rrun ★54](https://github.com/buster/rrun) — a command launcher for Linux, similar to gmrun  [<img src="https://travis-ci.org/buster/rrun.svg?branch=master">](https://travis-ci.org/buster/rrun)
  * [cristianoliveira/funzzy ★47](https://github.com/cristianoliveira/funzzy) — a configurable filesystem watcher inspired by [entr](http://entrproject.org/) [<img src="https://api.travis-ci.org/cristianoliveira/funzzy.svg?branch=master">](https://travis-ci.org/cristianoliveira/funzzy)
  * [derniercri/snatch ★558](https://github.com/derniercri/snatch) — a download accelerator [<img src="https://travis-ci.org/derniercri/snatch.svg?branch=master">](https://travis-ci.org/derniercri/snatch)
  * [mmstick/parallel ★720](https://github.com/mmstick/parallel) — a command-line CPU load balancer
  * [mmstick/systemd-manager ★350](https://github.com/mmstick/systemd-manager) — a systemd service manager written in Rust using GTK-rs.
  * [mmstick/tv-renamer ★64](https://github.com/mmstick/tv-renamer) — a tv series renaming application with an optional GTK3 frontend. [<img src="https://travis-ci.org/mmstick/tv-renamer.svg?branch=master">](https://travis-ci.org/mmstick/tv-renamer)
  * [ogham/exa ★1004](https://github.com/ogham/exa) — a replacement for 'ls' [<img src="https://travis-ci.org/ogham/exa.svg?branch=master">](https://travis-ci.org/ogham/exa)
  * [uutils/coreutils ★3317](https://github.com/uutils/coreutils) — a cross-platform Rust rewrite of the GNU coreutils [<img src="https://travis-ci.org/uutils/coreutils.svg?branch=master">](https://travis-ci.org/uutils/coreutils)
* **Text editors**
  * [gchp/iota ★961](https://github.com/gchp/iota) — a simple text editor [<img src="https://travis-ci.org/gchp/iota.svg?branch=master">](https://travis-ci.org/gchp/iota)
  * [mathall/rim ★337](https://github.com/mathall/rim) — Vim-like text editor written in Rust [<img src="https://travis-ci.org/mathall/rim.svg?branch=master">](https://travis-ci.org/mathall/rim)
  * [xi-editor ★7717](https://github.com/google/xi-editor) — a modern editor with a backend written in Rust.
* **Text processing**
  * [BurntSushi/ripgrep ★4376](https://github.com/BurntSushi/ripgrep) — combines the usability of The Silver Searcher with the raw speed of grep [<img src="https://travis-ci.org/BurntSushi/ripgrep.svg?branch=master">](https://travis-ci.org/BurntSushi/ripgrep)
  * [BurntSushi/xsv](https://github.com/BurntSushi/xsv) — a fast CSV command line tool (slicing, indexing, selecting, searching, sampling, etc.) [<img src="https://travis-ci.org/BurntSushi/xsv.svg?branch=master">](https://travis-ci.org/BurntSushi/xsv)
* **Utilities**
  * [yaa110/rubigo ★15](https://github.com/yaa110/rubigo) — Golang dependency tool and package manager, written in Rust [<img src="https://travis-ci.org/yaa110/rubigo.svg?branch=master">](https://travis-ci.org/yaa110/rubigo)
* **Virtualization**
  * [tailhook/vagga ★1110](https://github.com/tailhook/vagga) — a containerization tool without daemons [<img src="https://travis-ci.org/tailhook/vagga.svg?branch=master">](https://travis-ci.org/tailhook/vagga)
* **Window Managers**
  * [way-cooler/way-cooler](https://github.com/way-cooler/way-cooler) — a customizable Wayland compositor (window manager) [<img src="https://travis-ci.org/way-cooler/way-cooler.svg?branch=master">](https://travis-ci.org/way-cooler/way-cooler)

## Development tools

* [Clippy ★1250](https://github.com/Manishearth/rust-clippy) [[clippy](https://crates.io/crates/clippy)] — Rust lints [<img src="https://travis-ci.org/Manishearth/rust-clippy.svg?branch=master">](https://travis-ci.org/Manishearth/rust-clippy)
  * [Clippy Service](https://clippy.bashy.io/)
* [clog-tool/clog-cli ★293](https://github.com/clog-tool/clog-cli) — generates a changelog from git metadata ([conventional changelog](http://blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html)) [<img src="https://travis-ci.org/clog-tool/clog-cli.svg?branch=master">](https://travis-ci.org/clog-tool/clog-cli)
* [dan-t/rusty-tags ★125](https://github.com/dan-t/rusty-tags) — create ctags/etags for a cargo project and all of its dependencies [<img src="https://travis-ci.org/dan-t/rusty-tags.svg?branch=master">](https://travis-ci.org/dan-t/rusty-tags)
* [frewsxcv/crate-deps ★15 ⏳1Y](https://github.com/frewsxcv/crate-deps) — generates images of dependency graphs for crates hosted on crates.io
* [git-journal ★168](https://github.com/saschagrunert/git-journal) — The Git Commit Message and Changelog Generation Framework [<img src="https://travis-ci.org/saschagrunert/git-journal.svg?branch=master">](https://travis-ci.org/saschagrunert/git-journal)
* [killercup/rustfix ★85](https://github.com/killercup/rustfix)  — automatically applies the suggestions made by rustc [<img src="https://travis-ci.org/killercup/rustfix.svg?branch=master">](https://travis-ci.org/killercup/rustfix)
* [Racer ★2047](https://github.com/phildawes/racer) — code completion for Rust [<img src="https://travis-ci.org/phildawes/racer.svg?branch=master">](https://travis-ci.org/phildawes/racer)
* [rustfmt ★1082](https://github.com/rust-lang-nursery/rustfmt) — a Rust code formatter [<img src="https://travis-ci.org/rust-lang-nursery/rustfmt.svg?branch=master">](https://travis-ci.org/rust-lang-nursery/rustfmt)
* [Rustup ★1148](https://github.com/rust-lang-nursery/rustup.rs) — the Rust toolchain installer [<img src="https://travis-ci.org/rust-lang-nursery/rustup.rs.svg?branch=master">](https://travis-ci.org/rust-lang-nursery/rustup.rs)
* [Rust Language Server](https://github.com/jonathandturner/rls) — a server that runs in the background, providing IDEs, editors, and other tools with information about Rust programs
* [artifact ★199](https://github.com/vitiral/artifact) — the design doc tool made for developers [![Build Status](https://travis-ci.org/vitiral/artifact.svg?branch=master)](https://travis-ci.org/vitiral/artifact)
* [semantic-rs ★91](https://github.com/semantic-rs/semantic-rs) — automatic crate publishing [<img src="https://travis-ci.org/semantic-rs/semantic-rs.svg?branch=master">](https://travis-ci.org/semantic-rs/semantic-rs)

### Build system

* [Cargo](https://crates.io/) — the Rust package manager
  * [rsolomo/cargo-check ★86](https://github.com/rsolomo/cargo-check) [[cargo-check](https://crates.io/crates/cargo-check)] — a wrapper around `cargo rustc -- -Zno-trans` which can be helpful for running a faster compile if you only need correctness checks [<img src="https://travis-ci.org/rsolomo/cargo-check.svg?branch=master">](https://travis-ci.org/rsolomo/cargo-check)
  * [kbknapp/cargo-count ★56](https://github.com/kbknapp/cargo-count) [[cargo-count](https://crates.io/crates/cargo-count)] — lists source code counts and details about cargo projects, including unsafe statistics [<img src="https://travis-ci.org/kbknapp/cargo-count.svg?branch=master">](https://travis-ci.org/kbknapp/cargo-count)
  * [pwoolcoc/cargo-do ★10 ⏳1Y](https://github.com/pwoolcoc/cargo-do) [[cargo-do](https://crates.io/crates/cargo-do)] — run multiple cargo commands in a row
  * [maxsnew/cargo-dot ★32 ⏳1Y](https://github.com/maxsnew/cargo-dot) — generate graphs of a Cargo project's dependencies [<img src="https://travis-ci.org/maxsnew/cargo-dot.svg?branch=master">](https://travis-ci.org/maxsnew/cargo-dot)
  * [killercup/cargo-edit ★189](https://github.com/killercup/cargo-edit) [[cargo-edit](https://crates.io/crates/cargo-edit)] — allows you to add and list dependencies by reading/writing to your Cargo.toml file from the command line [<img src="https://travis-ci.org/killercup/cargo-edit.svg?branch=master">](https://travis-ci.org/killercup/cargo-edit)
  * [kbknapp/cargo-graph ★50](https://github.com/kbknapp/cargo-graph) [[cargo-graph](https://crates.io/crates/cargo-graph)] — updated fork of `cargo-dot` with additional features [<img src="https://travis-ci.org/kbknapp/cargo-graph.svg?branch=master">](https://travis-ci.org/kbknapp/cargo-graph)
  * [imp/cargo-info](https://gitlab.com/imp/cargo-info) [[cargo-info](https://crates.io/crates/cargo-info)] — queries crates.io for crates details from command line [<img src="https://travis-ci.org/imp/cargo-info.svg?branch=master">](https://travis-ci.org/imp/cargo-info)
  * [regexident/cargo-modules ★90](https://github.com/regexident/cargo-modules) [[cargo-modules](https://crates.io/crates/cargo-modules)] — A cargo plugin for showing a tree-like overview of a crate's modules. [<img src="https://travis-ci.org/regexident/cargo-modules.svg?branch=master">](https://travis-ci.org/regexident/cargo-modules)
  * [imp/cargo-multi ★0](https://github.com/imp/cargo-multi) [[cargo-multi](https://crates.io/crates/cargo-multi)] — runs specified cargo command on multiple crates [<img src="https://travis-ci.org/imp/cargo-multi.svg?branch=master">](https://travis-ci.org/imp/cargo-multi)
  * [kbknapp/cargo-outdated ★85](https://github.com/kbknapp/cargo-outdated) [[cargo-outdated](https://crates.io/crates/cargo-outdated)] — displays when newer versions of Rust dependencies are available, or out of date [<img src="https://travis-ci.org/kbknapp/cargo-outdated.svg?branch=master">](https://travis-ci.org/kbknapp/cargo-outdated)
  * [sunng87/cargo-release ★63](https://github.com/sunng87/cargo-release) [[cargo-release](https://crates.io/crates/cargo-release)] — tool for releasing git-managed cargo project, build, tag, publish, doc and push
  * [DanielKeep/cargo-script ★111](https://github.com/DanielKeep/cargo-script) [[cargo-script](https://crates.io/crates/cargo-script)] — lets people quickly and easily run Rust "scripts" which can make use of Cargo's package ecosystem
  * [passcod/cargo-watch ★231](https://github.com/passcod/cargo-watch) [[cargo-watch](https://crates.io/crates/cargo-watch)] — utility for cargo to compile projects when sources change [<img src="https://travis-ci.org/passcod/cargo-watch.svg?branch=master">](https://travis-ci.org/passcod/cargo-watch)
  * [BurntSushi/cargo-benchcmp ★79](https://github.com/BurntSushi/cargo-benchcmp) [[cargo-benchcmp](https://crates.io/crates/cargo-benchcmp)] — utility to compare Rust micro-benchmarks
* CMake
  * [SiegeLord/RustCMake ★58 ⏳1Y](https://github.com/SiegeLord/RustCMake) — an example project showing usage of CMake with Rust [<img src="https://travis-ci.org/SiegeLord/RustCMake.svg?branch=master">](https://travis-ci.org/SiegeLord/RustCMake)


### Debugging

* GDB
  * [rust-gdb](https://github.com/rust-lang/rust/blob/master/src/etc/rust-gdb)
  * [gdbgui ★2794](https://github.com/cs01/gdbgui) — Browser based frontend for gdb to debug C, C++, Rust, and go. [<img src="https://travis-ci.org/cs01/gdbgui.svg?branch=master">](https://travis-ci.org/cs01/gdbgui)
* LLDB
  * [lldb_batchmode.py](https://github.com/rust-lang/rust/blob/master/src/etc/lldb_batchmode.py) — allows to use LLDB in a way similar to GDB's batch mode.
  * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) — a LLDB extension for [Visual Studio Code](https://code.visualstudio.com/).
* rr
  * [rr](http://rr-project.org/) — rr is a lightweight tool for recording and replaying execution of applications

### Deployment

* Docker
  * [emk/rust-musl-builder ★174](https://github.com/emk/rust-musl-builder) — Docker images for compiling static Rust binaries using musl-libc and musl-gcc, with static versions of useful C libraries
  * [kpcyrd/mini-docker-rust ★2](https://github.com/kpcyrd/mini-docker-rust) — An example project for very small rust docker images [<img src="https://travis-ci.org/kpcyrd/mini-docker-rust.svg?branch=master">](https://travis-ci.org/kpcyrd/mini-docker-rust)
* Google App Engine
  * [DenisKolodin/rust-app-engine ★14](https://github.com/DenisKolodin/rust-app-engine) — App Engine Rust boilerplate
* Heroku
  * [emk/heroku-buildpack-rust ★109](https://github.com/emk/heroku-buildpack-rust) — a buildpack for Rust applications on Heroku

### Embedded

[Rust Embedded](http://www.rust-embedded.org)

* Cross compiling
  * [japaric/rust-cross ★516](https://github.com/japaric/rust-cross) — everything you need to know about cross compiling Rust programs [<img src="https://travis-ci.org/japaric/rust-cross.svg?branch=master">](https://travis-ci.org/japaric/rust-cross)
  * [japaric/xargo ★279](https://github.com/japaric/xargo) — effortless cross compilation of Rust programs to custom bare-metal targets like ARM Cortex-M [<img src="https://travis-ci.org/japaric/xargo.svg?branch=master">](https://travis-ci.org/japaric/xargo)
* Raspberry Pi
  * [Ogeon/rust-on-raspberry-pi ★219](https://github.com/Ogeon/rust-on-raspberry-pi) — instructions for how to cross compile Rust projects for the Raspberry Pi .


### FFI

See also [Foreign Function Interface](https://doc.rust-lang.org/book/ffi.html),  [The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/) (a collection of examples of using code written in Rust from other languages) and [FFI examples written in Rust ★197 ⏳1Y](https://github.com/alexcrichton/rust-ffi-examples).

* C
  * [Sean1708/rusty-cheddar ★150](https://github.com/Sean1708/rusty-cheddar) — generates C header files from Rust source files [<img src="https://travis-ci.org/Sean1708/rusty-cheddar.svg?branch=master">](https://travis-ci.org/Sean1708/rusty-cheddar)
* C++
  * [servo/rust-bindgen ★259](https://github.com/servo/rust-bindgen) — a Rust bindings generator
* Erlang
  * [hansihe/Rustler ★553](https://github.com/hansihe/Rustler) — safe Rust bridge for creating Erlang NIF functions [<img src="https://travis-ci.org/hansihe/Rustler.svg?branch=master">](https://travis-ci.org/hansihe/Rustler)
* Haskell
  * [mgattozzi/curryrs ★85](https://github.com/mgattozzi/curryrs) — Bridge the gap between Haskell and Rust
  * [mgattozzi/haskellrs ★5](https://github.com/mgattozzi/haskellrs) — Rust in Haskell FFI Example
  * [mgattozzi/rushs ★0](https://github.com/mgattozzi/rushs) — Haskell in Rust FFI Example
* Java
  * [drrb/java-rust-example ★160 ⏳1Y](https://github.com/drrb/java-rust-example) — use Rust from Java [<img src="https://travis-ci.org/drrb/java-rust-example.svg?branch=master">](https://travis-ci.org/drrb/java-rust-example)
  * [GravityScore/RustJNI](https://github.com/GravityScore/RustJNI) — use Java from Rust [<img src="https://travis-ci.org/GravityScore/RustJNI.svg?branch=master">](https://travis-ci.org/GravityScore/RustJNI)
  * [kud1ing/rucaja ★6](https://github.com/kud1ing/rucaja) [[rucaja](https://crates.io/crates/rucaja)] — use Java from Rust [<img src="https://travis-ci.org/kud1ing/rucaja.svg?branch=master">](https://travis-ci.org/kud1ing/rucaja)
  * [prevoty/jni-rs ★33](https://github.com/prevoty/jni-rs) [[jni](https://crates.io/crates/jni)] — use Rust from Java [<img src="https://travis-ci.org/prevoty/jni-rs.svg?branch=master">](https://travis-ci.org/prevoty/jni-rs)
  * [sfackler/rust-jni-sys ★15](https://github.com/sfackler/rust-jni-sys) [[jni-sys](https://crates.io/crates/jni-sys)] — Rust definitions corresponding to jni.h [<img src="https://travis-ci.org/sfackler/rust-jni-sys.svg?branch=master">](https://travis-ci.org/sfackler/rust-jni-sys)
* Lua
  * [jcmoyer/rust-lua53 ★61](https://github.com/jcmoyer/rust-lua53) — Lua 5.3 bindings for Rust [<img src="https://travis-ci.org/jcmoyer/rust-lua53.svg?branch=master">](https://travis-ci.org/jcmoyer/rust-lua53)
  * [kballard/rust-lua ★96](https://github.com/kballard/rust-lua) — Safe Rust bindings to Lua 5.1 [<img src="https://travis-ci.org/kballard/rust-lua.svg">](https://travis-ci.org/kballard/rust-lua)
  * [tickbh/td_rlua ★18](https://github.com/tickbh/td_rlua) — Zero-cost high-level lua 5.3 wrapper for Rust [<img src="https://api.travis-ci.org/tickbh/td_rlua.svg?branch=master">](https://travis-ci.org/tickbh/td_rlua)
  * [tomaka/hlua ★272](https://github.com/tomaka/hlua) — Rust library to interface with Lua [<img src="https://travis-ci.org/tomaka/hlua.svg?branch=master">](https://travis-ci.org/tomaka/hlua)
* mruby
  * [anima-engine/mrusty ★151](https://github.com/anima-engine/mrusty) — mruby safe bindings for Rust [<img src="https://travis-ci.org/anima-engine/mrusty.svg?branch=master">](https://travis-ci.org/anima-engine/mrusty)
* Node.js
  * [rustbridge/neon](https://github.com/rustbridge/neon) — use Rust from Node.js [<img src="https://travis-ci.org/rustbridge/neon.svg?branch=master">](https://travis-ci.org/rustbridge/neon)
* Objective-C
  * [SSheldon/rust-objc ★99](https://github.com/SSheldon/rust-objc) — Objective-C Runtime bindings and wrapper for Rust
* Python
  * [dgrunwald/rust-cpython ★462](https://github.com/dgrunwald/rust-cpython) — Python bindings [<img src="https://travis-ci.org/dgrunwald/rust-cpython.svg?branch=master">](https://travis-ci.org/dgrunwald/rust-cpython)
* R
  * [rustr/rustr ★76](https://github.com/rustr/rustr) — use Rust from R, and use R in Rust [<img src="https://travis-ci.org/rustr/rustr.svg?branch=master">](https://travis-ci.org/rustr/rustr)
* Ruby
  * [d-unseductable/ruru ★608](https://github.com/d-unseductable/ruru) — native Ruby extensions written in Rust [<img src="https://travis-ci.org/d-unseductable/ruru.svg?branch=master">](https://travis-ci.org/d-unseductable/ruru)
  * [rustbridge/helix](https://github.com/rustbridge/helix) — write Ruby classes in Rust [<img src="https://travis-ci.org/rustbridge/helix.svg?branch=master">](https://travis-ci.org/rustbridge/helix)


### IDEs

See also [http://areweideyet.com/](http://areweideyet.com/) and [Rust and IDEs](https://www.rust-lang.org/ides.html).

  * [Atom](https://atom.io/)
    * [zargony/atom-language-rust ★103](https://github.com/zargony/atom-language-rust)
  * [Eclipse](https://eclipse.org/)
    * [RustDT ★335](https://github.com/RustDT/RustDT) — [<img src="https://travis-ci.org/RustDT/RustDT.svg?branch=master">](https://travis-ci.org/RustDT/RustDT)
  * [Emacs](https://www.gnu.org/software/emacs/)
    * [rust-mode ★210](https://github.com/rust-lang/rust-mode) — Rust Major Mode
    * [flycheck-rust](https://github.com/flycheck/flycheck-rust) — Rust support for [Flycheck ★1288](https://github.com/flycheck/flycheck)
    * [emacs-racer](https://github.com/racer-rust/emacs-racer) — Autocompletion (see also [company](https://company-mode.github.io) and [auto-complete](https://github.com/auto-complete/auto-complete))
  * [NetBeans](https://netbeans.org/)
    * [drrb/rust-netbeans ★37 ⏳2Y](https://github.com/drrb/rust-netbeans)
  * [IntelliJ](https://www.jetbrains.com/idea/)
    * [intellij-rust/intellij-rust ★1237](https://github.com/intellij-rust/intellij-rust) — [<img src="https://travis-ci.org/intellij-rust/intellij-rust.svg?branch=master">](https://travis-ci.org/intellij-rust/intellij-rust)
    * [intellij-rust/intellij-toml ★17](https://github.com/intellij-rust/intellij-toml) — basic Toml support
    * [JustSid/AfterglowIntelliJ ★55](https://github.com/JustSid/AfterglowIntelliJ) — custom icons
  * [Ride ★122](https://github.com/madeso/ride) — [<img src="https://travis-ci.org/madeso/ride.svg?branch=master">](https://travis-ci.org/madeso/ride)
  * [SolidOak](https://github.com/oakes/SolidOak) — a simple IDE for Rust, based on GTK+ and [Neovim ★22397](https://github.com/neovim/neovim)
  * [Vim](http://www.vim.org/) — the ubiquitous text editor
	* [rust.vim ★701](https://github.com/rust-lang/rust.vim) — provides file detection, syntax highlighting, formatting, Syntastic integration, and more.
	* [vim-cargo ★15](https://github.com/timonv/vim-cargo) — command bindings to quickly run cargo stuff from vim.
	* [vim-racer](https://github.com/racer-rust/vim-racer) — allows vim to use [Racer ★2047](https://github.com/phildawes/racer) for Rust code completion and navigation.
  * Visual Studio
    * [PistonDevelopers/VisualRust ★523](https://github.com/PistonDevelopers/VisualRust) — a Visual Studio extension for Rust [<img src="https://travis-ci.org/PistonDevelopers/VisualRust.svg?branch=master">](https://travis-ci.org/PistonDevelopers/VisualRust)
  * [Visual Studio Code](https://code.visualstudio.com/)
    * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) — a LLDB extension
    * [KalitaAlexey/vscode-rust](https://marketplace.visualstudio.com/items?itemName=kalitaalexey.vscode-rust) — a fork of RustyCode
    * [saviorisdead/RustyCode](https://marketplace.visualstudio.com/items?itemName=saviorisdead.RustyCode) (unmaintained)
  * [gnome-builder](https://wiki.gnome.org/Apps/Builder) native support for rust and cargo since Version 3.22.2


### Pattern Recognition

* [sfikas/rusteval ★8](https://github.com/sfikas/rusteval) — A tool used to evaluate the output of retrieval algorithms [![Build Status](https://travis-ci.org/sfikas/rusteval.svg?branch=master)](https://travis-ci.org/sfikas/rusteval)

### Profiling

* [ellisonch/rust-stopwatch ★28](https://github.com/ellisonch/rust-stopwatch) — a stopwatch library [<img src="https://travis-ci.org/ellisonch/rust-stopwatch.svg?branch=master">](https://travis-ci.org/ellisonch/rust-stopwatch)
* FlameGraphs
  * [mrhooray/torch ★79](https://github.com/mrhooray/torch) — generates FlameGraphs based on DWARF Debug Info
  * [TyOverby/flame ★151](https://github.com/TyOverby/flame) — [<img src="https://travis-ci.org/TyOverby/flame.svg?branch=master">](https://travis-ci.org/TyOverby/flame)


### Testing

[[testing](https://crates.io/keywords/testing)]

* [BurntSushi/quickcheck ★573](https://github.com/BurntSushi/quickcheck) [[quickcheck](https://crates.io/crates/quickcheck)] — a Rust implementation of [QuickCheck](https://wiki.haskell.org/Introduction_to_QuickCheck1) [<img src="https://travis-ci.org/BurntSushi/quickcheck.svg?branch=master">](https://travis-ci.org/BurntSushi/quickcheck)
* [farcaller/shiny ★82](https://github.com/farcaller/shiny) — a fancy syntax similar to Ruby's Rspec or Objective-C' kiwi [<img src="https://travis-ci.org/farcaller/shiny.svg?branch=master">](https://travis-ci.org/farcaller/shiny)
* [frewsxcv/afl.rs](https://github.com/frewsxcv/afl.rs) — a Rust fuzzer, using [AFL](http://lcamtuf.coredump.cx/afl/) [<img src="https://api.travis-ci.org/frewsxcv/afl.rs.svg?branch=master">](https://travis-ci.org/frewsxcv/afl.rs)
* [reem/stainless ★292](https://github.com/reem/stainless) [[stainless](https://crates.io/crates/stainless)] — Organized, flexible testing framework [<img src="https://travis-ci.org/reem/stainless.svg?branch=master">](https://travis-ci.org/reem/stainless)
* [AlKass/polish ★12](https://github.com/AlKass/polish)Mini Testing/Test-Driven Framework [![Build Status](https://travis-ci.org/AlKass/polish.svg?branch=master)](https://travis-ci.org/AlKass/polish)


## Libraries

### Astronomy

[[astronomy](https://crates.io/keywords/astronomy)]

* [saurvs/astro-rust ★47](https://github.com/saurvs/astro-rust) — astronomy for Rust [<img src="https://travis-ci.org/saurvs/astro-rust.svg?branch=master">](https://travis-ci.org/saurvs/astro-rust)
* [mindriot101/rust-fitsio ★1](https://github.com/mindriot101/rust-fitsio) [[fitsio](https://crates.io/crates/fitsio)] — fits interface library wrapping cfitsio [<img src="https://travis-ci.org/mindriot101/rust-fitsio.svg?branch=master">](https://travis-ci.org/mindriot101/rust-fitsio)
* [flosse/rust-sun ★7](https://github.com/flosse/rust-sun) — A rust port of the JS library suncalc [<img src="https://travis-ci.org/flosse/rust-sun.svg?branch=master">](https://travis-ci.org/flosse/rust-sun)


### Asynchronous

* [zonyitoo/coio-rs ★313](https://github.com/zonyitoo/coio-rs) — a coroutine I/O library with a working-stealing scheduler [<img src="https://travis-ci.org/zonyitoo/coio-rs.svg?branch=master">](https://travis-ci.org/zonyitoo/coio-rs)
* [dpc/mioco ★14](https://github.com/dpc/mioco) — Scalable, coroutine-based, asynchronous IO handling library [<img src="https://img.shields.io/travis/dpc/mioco/master.svg?style=flat-square" alt="Travis CI Build Status">](https://travis-ci.org/dpc/mioco)
* [alexcrichton/futures-rs ★1457](https://github.com/alexcrichton/futures-rs) — Zero-cost futures in Rust [<img src="https://travis-ci.org/alexcrichton/futures-rs.svg?branch=master" alt="Travis CI Build Status">](https://travis-ci.org/alexcrichton/futures-rs)
* [carllerche/mio ★2029](https://github.com/carllerche/mio) — MIO is a lightweight IO library for Rust with a focus on adding as little overhead as possible over the OS abstractions [<img src="https://travis-ci.org/carllerche/mio.svg?branch=master">](https://travis-ci.org/carllerche/mio)


### Audio

[[audio](https://crates.io/keywords/audio)]

* [GuillaumeGomez/rust-fmod ★12](https://github.com/GuillaumeGomez/rust-fmod) — [FMOD](http://www.fmod.org/) bindings [![Build Status](https://api.travis-ci.org/GuillaumeGomez/rust-fmod.svg?branch=master)](https://travis-ci.org/GuillaumeGomez/rust-fmod)
* [jhasse/ears ★25](https://github.com/jhasse/ears) — a simple library to play Sounds and Musics, on top of OpenAL and libsndfile [<img src="https://travis-ci.org/jhasse/ears.svg?branch=master">](https://travis-ci.org/jhasse/ears)
* [jpernst/openal-rs](https://github.com/jpernst/openal-rs) — [OpenAL 1.1](http://www.openal.org/) bindings [<img src="https://travis-ci.org/jpernst/openal-rs.svg?branch=master">](https://travis-ci.org/jpernst/openal-rs)
* [musitdev/portmidi-rs ★34](https://github.com/musitdev/portmidi-rs) — [PortMidi](http://portmedia.sourceforge.net/portmidi/) bindings [<img src="https://travis-ci.org/musitdev/portmidi-rs.svg?branch=master">](https://travis-ci.org/musitdev/portmidi-rs)
* [ruuda/hound ★60](https://github.com/ruuda/hound) [[Hound](https://crates.io/crates/hound)] — A WAV encoding and decoding library [<img src="https://travis-ci.org/ruuda/hound.svg?branch=master">](https://travis-ci.org/ruuda/hound)
* [RustAudio](https://github.com/RustAudio)
  * [RustAudio/rust-portaudio ★108](https://github.com/RustAudio/rust-portaudio) — [PortAudio](http://www.portaudio.com/) bindings [<img src="https://travis-ci.org/RustAudio/rust-portaudio.svg?branch=master">](https://travis-ci.org/RustAudio/rust-portaudio)


### Authentication

* [keats/rust-jwt](https://github.com/keats/rust-jwt) — [JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) lib in rust  [![Build Status](https://api.travis-ci.org/Keats/rust-jwt.svg?branch=master)](https://travis-ci.org/Keats/rust-jwt)
* [hngiang/rust-accountkit](https://github.com/hngiang/rust-accountkit) — An implementation [Facebook AccountKit](https://developers.facebook.com/docs/accountkit) for Rust [![Build Status](https://travis-ci.org/hngiang/rust-accountkit.svg?branch=master)](https://travis-ci.org/hngiang/rust-accountkit)

### Bioinformatics

* [Rust-Bio](https://github.com/rust-bio) — bioinformatics libraries in Rust.


### Caching

* [jaysonsantos/bmemcached-rs ★9 ⏳1Y](https://github.com/jaysonsantos/bmemcached-rs) — Memcached library written in pure rust [<img src="https://travis-ci.org/jaysonsantos/bmemcached-rs.svg?branch=master">](https://travis-ci.org/jaysonsantos/bmemcached-rs)


### Concurrency

* [aturon/crossbeam](https://github.com/aturon/crossbeam) – Support for parallelism and low-level concurrency in Rust [<img src="https://travis-ci.org/aturon/crossbeam.svg?branch=master">](https://travis-ci.org/aturon/crossbeam)
* [nikomatsakis/rayon ★973](https://github.com/nikomatsakis/rayon) – A data parallelism library for Rust [<img src="https://travis-ci.org/nikomatsakis/rayon.svg?branch=master">](https://travis-ci.org/nikomatsakis/rayon)
* [rustcc/coroutine-rs ★267](https://github.com/rustcc/coroutine-rs) – Coroutine Library in Rust [<img src="https://img.shields.io/travis/rustcc/coroutine-rs.svg">](https://travis-ci.org/rustcc/coroutine-rs)
* [zonyitoo/coio-rs ★313](https://github.com/zonyitoo/coio-rs) – Coroutine I/O for Rust [<img src="https://travis-ci.org/zonyitoo/coio-rs.svg?branch=master">](https://travis-ci.org/zonyitoo/coio-rs)


### Cloud

* AWS [[aws](https://crates.io/keywords/aws)]
  * [rusoto/rusoto ★327](https://github.com/rusoto/rusoto) — [<img src="https://travis-ci.org/rusoto/rusoto.svg?branch=master">](https://travis-ci.org/rusoto/rusoto)
* DigitalOcean
  * [kbknapp/doapi ★18](https://github.com/kbknapp/doapi-rs) — DigitalOcean v2 API bindings [<img src="https://travis-ci.org/kbknapp/doapi-rs.svg?branch=master">](https://travis-ci.org/kbknapp/doapi-rs)


### Command-line argument parsing

* [docopt/docopt.rs ★463](https://github.com/docopt/docopt.rs) — a Rust implementation of [DocOpt](http://docopt.org) [<img src="https://travis-ci.org/docopt/docopt.rs.svg?branch=master">](https://travis-ci.org/docopt/docopt.rs)
* [kbknapp/clap-rs ★1054](https://github.com/kbknapp/clap-rs) — a simple to use, full featured command-line argument parser [<img src="https://travis-ci.org/kbknapp/clap-rs.svg?branch=master">](https://travis-ci.org/kbknapp/clap-rs)


### Command-line interface

* [kkawakam/rustyline ★89](https://github.com/kkawakam/rustyline) — Readline Implementation in Rust [![Build Status](https://travis-ci.org/kkawakam/rustyline.svg?branch=master)](https://travis-ci.org/kkawakam/rustyline)
* [srijs/rust-copperline ★22](https://github.com/srijs/rust-copperline) — pure-Rust Command Line Editing Library


### Compression

* brotli
  * [ende76/brotli-rs ★38](https://github.com/ende76/brotli-rs) — implementation of [Brotli](http://google-opensource.blogspot.co.uk/2015/09/introducing-brotli-new-compression.html) compression
  * [dropbox/rust-brotli ★145](https://github.com/dropbox/rust-brotli) — Brotli decompressor in Rust that optionally avoids the stdlib
* bzip2
  * [alexcrichton/bzip2-rs ★10](https://github.com/alexcrichton/bzip2-rs) — [libbz2](http://www.bzip.org) bindings [<img src="https://travis-ci.org/alexcrichton/bzip2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/bzip2-rs)
* miniz
  * [alexcrichton/flate2-rs ★94](https://github.com/alexcrichton/flate2-rs) — [miniz](https://code.google.com/p/miniz/) bindings [<img src="https://travis-ci.org/alexcrichton/flate2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/flate2-rs)
* snappy
  * [JeffBelgum/rust-snappy](https://github.com/JeffBelgum/rust-snappy) — [snappy ★1884](https://github.com/google/snappy) bindings [<img src="https://travis-ci.org/JeffBelgum/rust-snappy.svg?branch=master">](https://travis-ci.org/JeffBelgum/rust-snappy)
* tar
  * [alexcrichton/tar-rs ★59](https://github.com/alexcrichton/tar-rs) — tar archive reading/writing in Rust [<img src="https://travis-ci.org/alexcrichton/tar-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/tar-rs)
* zip
  * [mvdnes/zip-rs ★53](https://github.com/mvdnes/zip-rs) — read and write ZIP archives [![Build Status](https://travis-ci.org/mvdnes/zip-rs.svg?branch=master)](https://travis-ci.org/mvdnes/zip-rs)


### Computation

* [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) [[blas](https://crates.io/keywords/blas)]
  * [mikkyang/rust-blas ★51](https://github.com/mikkyang/rust-blas) — BLAS bindings
  * [stainless-steel/blas ★15](https://github.com/stainless-steel/blas) — BLAS bindings [<img src="https://travis-ci.org/stainless-steel/blas.svg?branch=master">](https://travis-ci.org/stainless-steel/blas)
* [Conjugate Gradient](https://en.wikipedia.org/wiki/Limited-memory_BFGS) [[CG+](http://users.iems.northwestern.edu/~nocedal/CG+.html)]
  * [noshu/cg-sys ★1](https://github.com/noshu/cg-sys) — Rust binding of fortran CG+ subroutine
* [GMP](https://gmplib.org/)
  * [thestinger/rust-gmp ★32 ⏳1Y](https://github.com/thestinger/rust-gmp) — libgmp bindings [<img src="https://travis-ci.org/thestinger/rust-gmp.svg?branch=master">](https://travis-ci.org/thestinger/rust-gmp)
* [GSL](http://www.gnu.org/software/gsl/)
  * [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez) — GSL bindings [<img src="https://travis-ci.org/GuillaumeGomez/rust-GSL.svg?branch=master">](https://travis-ci.org/GuillaumeGomez/rust-GSL)
* [LAPACK](https://en.wikipedia.org/wiki/LAPACK)
  * [stainless-steel/lapack ★26](https://github.com/stainless-steel/lapack) — LAPACK bindings [<img src="https://travis-ci.org/stainless-steel/lapack.svg?branch=master">](https://travis-ci.org/stainless-steel/lapack)
* [L-BFGS-B](https://en.wikipedia.org/wiki/Limited-memory_BFGS) [[lbfgsb](http://users.iems.northwestern.edu/~nocedal/lbfgsb.html)]
  * [noshu/lbfgsb-sys ★0](https://github.com/noshu/lbfgsb-sys) — Rust binding of fortran L-BFGS-B subroutine
* [sebcrozet/nalgebra ★439](https://github.com/sebcrozet/nalgebra) — low-dimensional linear algebra library [<img src="sebcrozet/nalgebra.svg?branch=master">](https://travis-ci.org/sebcrozet/nalgebra)
* Parallel
  * [arrayfire/arrayfire-rust ★170](https://github.com/arrayfire/arrayfire-rust) — [Arrayfire](http://arrayfire.com) bindings
  * [autumnai/collenchyma ★346 ⏳1Y](https://github.com/autumnai/collenchyma) — An extensible, pluggable, backend-agnostic framework for parallel, high-performance computations on CUDA, OpenCL and common host CPU. [<img src="https://travis-ci.org/autumnai/collenchyma.svg?branch=master">](https://travis-ci.org/autumnai/collenchyma)
  * [luqmana/rust-opencl ★135](https://github.com/luqmana/rust-opencl) — [OpenCL](https://www.khronos.org/opencl/) bindings [<img src="https://travis-ci.org/luqmana/rust-opencl.svg?branch=master">](https://travis-ci.org/luqmana/rust-opencl)
* Scirust
  * [indigits/scirust ★110](https://github.com/indigits/scirust) — scientific computing library in Rust [![Build Status](https://travis-ci.org/indigits/scirust.svg?branch=master)](https://travis-ci.org/indigits/scirust)
* Statrs
  * [boxtown/statrs ★63](https://github.com/boxtown/statrs) — Robust statistical computation library in Rust [![Build Status](https://travis-ci.org/boxtown/statrs.svg?branch=master)](https://travis-ci.org/boxtown/statrs)
* Rustimization [[rustimization](https://crates.io/crates/rustimization)]
  * [noshu/rustimization ★7](https://github.com/noshu/rustimization) — A rust optimization library which includes L-BFGS-B and Conjugate Gradient algorithm


### Configuration

* [mehcode/config-rs ★95](https://github.com/mehcode/config-rs) [[config](https://crates.io/crates/config)] — Layered configuration system for Rust applications (with strong support for 12-factor applications). [<img src="https://travis-ci.org/mehcode/config-rs.svg?branch=master">](https://travis-ci.org/mehcode/config-rs)


### Cryptography

[[crypto](https://crates.io/keywords/crypto), [cryptography](https://crates.io/keywords/cryptography)]

* [briansmith/ring ★490](https://github.com/briansmith/ring) — Safe, fast, small crypto using Rust and BoringSSL's cryptography primitives. [<img src="https://travis-ci.org/briansmith/ring.svg?branch=master">](https://travis-ci.org/briansmith/ring)
* [briansmith/webpki ★86](https://github.com/briansmith/webpki) — Web PKI TLS X.509 certificate validation in Rust. [<img src="https://travis-ci.org/briansmith/webpki.svg?branch=master">](https://travis-ci.org/briansmith/webpki)
* [ctz/rustls ★499](https://github.com/ctz/rustls) — a Rust implementation of TLS
* [DaGenix/rust-crypto ★564](https://github.com/DaGenix/rust-crypto) — cryptographic algorithms in Rust [<img src="https://travis-ci.org/DaGenix/rust-crypto.svg?branch=master">](https://travis-ci.org/DaGenix/rust-crypto)
* [dnaq/sodiumoxide](https://github.com/dnaq/sodiumoxide) — [libsodium ★4080](https://github.com/jedisct1/libsodium) bindings [<img src="https://travis-ci.org/dnaq/sodiumoxide.svg?branch=master">](https://travis-ci.org/dnaq/sodiumoxide)
* [klutzy/suruga ★127 ⏳1Y](https://github.com/klutzy/suruga) — a Rust implementation of [TLS 1.2](http://tools.ietf.org/html/rfc5246)
* [libOctavo/octavo ★115](https://github.com/libOctavo/octavo) — Modular hash and crypto library in Rust [<img src="https://api.travis-ci.org/libOctavo/octavo.svg?branch=master">](https://travis-ci.org/libOctavo/octavo)
* [lispyclouds/mpw-rs ★11](https://github.com/lispyclouds/mpw-rs) — Pure Rust implementation of the Master Password password manager [<img src="https://travis-ci.org/lispyclouds/mpw-rs.svg?branch=master">](https://travis-ci.org/lispyclouds/mpw-rs)
* [sfackler/rust-native-tls ★57](https://github.com/sfackler/rust-native-tls) — Bindings for native TLS libraries
* [sfackler/rust-openssl ★269](https://github.com/sfackler/rust-openssl) — [OpenSSL](https://www.openssl.org/) bindings [<img src="https://travis-ci.org/sfackler/rust-openssl.svg?branch=master">](https://travis-ci.org/sfackler/rust-openssl)
* [sfackler/rust-security-framework](https://github.com/sfackler/rust-security-framework) — Bindings for Security Framework (OSX native crypto)
* [steffengy/schannel-rs](https://github.com/steffengy/schannel-rs) — Bindings for Schannel (Windows native TLS)
* [RNCryptor/rncryptor-rs ★3](https://github.com/RNCryptor/rncryptor-rs) — Pure Rust implementation of the RNCryptor AES file format
* [doublify/libblockchain ★2](https://github.com/doublify/libblockchain) - A Blockchain implementation [<img src="https://travis-ci.org/doublify/libblockchain.svg?branch=master">](https://travis-ci.org/doublify/libblockchain)



### Database

[[database](https://crates.io/keywords/database)]

* [sfackler/r2d2 ★161](https://github.com/sfackler/r2d2) — generic connection pool [<img src="https://travis-ci.org/sfackler/r2d2.svg?branch=master">](https://travis-ci.org/sfackler/r2d2)
* NoSQL [[nosql](https://crates.io/keywords/nosql)]
  * [Cassandra](http://cassandra.apache.org) [[cassandra](https://crates.io/keywords/cassandra), [cql](https://crates.io/keywords/cql)]
    * [AlexPikalov/cdrs ★69](https://github.com/AlexPikalov/cdrs) [[cdrs](https://crates.io/crates/cdrs)] — native client written in Rust [<img src="https://travis-ci.org/AlexPikalov/cdrs.svg?branch=master">](https://travis-ci.org/AlexPikalov/cdrs)
    * [tupshin/cassandra-rs ★47](https://github.com/tupshin/cassandra-rs) —  bindings to the C++ client [<img src="https://travis-ci.org/tupshin/cassandra-rs.svg?branch=master">](https://travis-ci.org/tupshin/cassandra-rs)
  * CouchDB [[couchdb](https://crates.io/keywords/couchdb)]
    * [chill-rs/chill ★15](https://github.com/chill-rs/chill) [[couchdb](https://crates.io/crates/chill)] — a Rust client for the CouchDB REST API [<img src="https://travis-ci.org/chill-rs/chill.svg?branch=master">](https://travis-ci.org/chill-rs/chill)
  * Elasticsearch [[elasticsearch](https://crates.io/keywords/elasticsearch)]
    * [benashford/rs-es ★106](https://github.com/benashford/rs-es) [[rs-es](https://crates.io/crates/rs-es)] — a Rust client for the [Elastic](https://www.elastic.co/) REST API [<img src="https://travis-ci.org/benashford/rs-es.svg?branch=master">](https://travis-ci.org/benashford/rs-es)
    * [elastic-rs/elastic-reqwest ★4](https://github.com/elastic-rs/elastic-reqwest) [[elastic_reqwest](https://crates.io/crates/elastic_reqwest)] — a lightweight implementation of the Elasticsearch API based on Reqwest [<img src="https://travis-ci.org/elastic-rs/elastic-reqwest.svg">](https://travis-ci.org/elastic-rs/elastic-reqwest)
  * etcd
    * [jimmycuadra/rust-etcd ★56](https://github.com/jimmycuadra/rust-etcd) [[etcd](https://crates.io/crates/etcd)] — A client library for CoreOS's etcd. [<img src="https://travis-ci.org/jimmycuadra/rust-etcd.svg?branch=master">](https://travis-ci.org/jimmycuadra/rust-etcd)
  * ForestDB
    * [vhbit/sherwood](https://github.com/vhbit/sherwood) — [ForestDB ★768](https://github.com/couchbase/forestdb) bindings [<img src="https://travis-ci.org/vhbit/sherwood.svg?branch=master">](https://travis-ci.org/vhbit/sherwood)
  * [InfluxDB](https://www.influxdata.com/)
    * [panoptix-za/influxdb-rs ★6](https://github.com/panoptix-za/influxdb-rs) — asynchronous interface [<img src="https://travis-ci.org/panoptix-za/influxdb-rs.svg?branch=master">](https://travis-ci.org/panoptix-za/influxdb-rs)
  * LevelDB
    * [skade/leveldb](https://github.com/skade/leveldb) — [LevelDB ★9177](https://github.com/google/leveldb) bindings [<img src="https://travis-ci.org/skade/leveldb.svg?branch=master">](https://travis-ci.org/skade/leveldb)
  * LMDB [[lmdb](https://crates.io/keywords/lmdb)]
    * [vhbit/lmdb-rs ★63](https://github.com/vhbit/lmdb-rs) [[lmdb-rs](https://crates.io/crates/lmdb-rs)] — [LMDB](http://symas.com/mdb/) bindings [<img src="https://travis-ci.org/vhbit/lmdb-rs.svg?branch=master">](https://travis-ci.org/vhbit/lmdb-rs)
  * MongoDB [[mongodb](https://crates.io/keywords/mongodb)]
    * [mongodb-labs/mongo-rust-driver-prototype ★168](https://github.com/mongodb-labs/mongo-rust-driver-prototype) [[mongodb](https://crates.io/crates/mongodb)] — [MongoDB](https://www.mongodb.org/) bindings [<img src="https://travis-ci.org/mongodb-labs/mongo-rust-driver-prototype.svg">](https://travis-ci.org/mongodb-labs/mongo-rust-driver-prototype)
  * Neo4j [[cypher](https://crates.io/keywords/cypher), [neo4j](https://crates.io/keywords/neo4j)]
  * Redis [[redis](https://crates.io/keywords/redis)]
    * [mitsuhiko/redis-rs ★596](https://github.com/mitsuhiko/redis-rs) — [Redis](http://redis.io) library in Rust [<img src="https://travis-ci.org/mitsuhiko/redis-rs.svg?branch=master">](https://travis-ci.org/mitsuhiko/redis-rs)
  * [RocksDB](http://rocksdb.org/)
    * [spacejam/rust-rocksdb ★135](https://github.com/spacejam/rust-rocksdb) — RocksDB bindings [<img src="https://travis-ci.org/spacejam/rust-rocksdb.svg?branch=master">](https://travis-ci.org/spacejam/rust-rocksdb)
  * [UnQLite](http://unqlite.org)
    * [zitsen/unqlite.rs ★14](https://github.com/zitsen/unqlite.rs) — UnQLite bindings [<img src="https://travis-ci.org/zitsen/unqlite.rs.svg?branch=master">](https://travis-ci.org/zitsen/unqlite.rs)
  * [ZooKeeper](https://zookeeper.apache.org/)
    * [bonifaido/rust-zookeeper ★43](https://github.com/bonifaido/rust-zookeeper) [[zookeeper](https://crates.io/crates/zookeeper)] — A client library for Apache ZooKeeper. [<img src="https://travis-ci.org/bonifaido/rust-zookeeper.svg?branch=master">](https://travis-ci.org/bonifaido/rust-zookeeper)
* SQL [[sql](https://crates.io/keywords/sql)]
  * Microsoft SQL
    * [steffengy/tiberius ★26](https://github.com/steffengy/tiberius) — [<img src="https://travis-ci.org/steffengy/tiberius.svg?branch=master">](https://travis-ci.org/steffengy/tiberius)
  * MySql [[mysql](https://crates.io/keywords/mysql)]
    * [AgilData/mysql-proxy-rs ★95](https://github.com/AgilData/mysql-proxy-rs) — a MySQL Proxy [<img src="https://travis-ci.org/AgilData/mysql-proxy-rs.svg?branch=master">](https://travis-ci.org/AgilData/mysql-proxy-rs)
    * [blackbeam/mysql_async ★23](https://github.com/blackbeam/mysql_async) [[mysql_async](https://crates.io/crates/mysql_async)] — asyncronous Rust Mysql driver based on Tokio. [<img src="https://travis-ci.org/blackbeam/mysql_async.svg?branch=master">](https://travis-ci.org/blackbeam/mysql_async)
    * [blackbeam/rust-mysql-simple ★145](https://github.com/blackbeam/rust-mysql-simple) [[mysql](https://crates.io/crates/mysql)] — a native MySql client [<img src="https://travis-ci.org/blackbeam/rust-mysql-simple.svg?branch=master">](https://travis-ci.org/blackbeam/rust-mysql-simple)
 * ORM [[orm](https://crates.io/keywords/orm)]
    * [diesel-rs/diesel ★1544](https://github.com/diesel-rs/diesel) — an ORM and Query builder for Rust [![Build Status](https://api.travis-ci.org/diesel-rs/diesel.svg)](https://travis-ci.org/diesel-rs/diesel)
    * [ivanceras/rustorm ★159](https://github.com/ivanceras/rustorm) — an ORM for Rust [![Build Status](https://api.travis-ci.org/ivanceras/rustorm.svg)](https://travis-ci.org/ivanceras/rustorm)
  * PostgreSql [[postgres](https://crates.io/keywords/postgres), [postgresql](https://crates.io/keywords/postgresql)]
    * [sfackler/rust-postgres ★717](https://github.com/sfackler/rust-postgres) [[postgres](https://crates.io/crates/postgres)] — a native [PostgreSQL](http://www.postgresql.org) client [<img src="https://travis-ci.org/sfackler/rust-postgres.svg?branch=master">](https://travis-ci.org/sfackler/rust-postgres)
  * Sqlite [[sqlite](https://crates.io/keywords/sqlite)]
    * [jgallagher/rusqlite ★179](https://github.com/jgallagher/rusqlite) — [Sqlite3](http://www.sqlite.org/) bindings [<img src="https://travis-ci.org/jgallagher/rusqlite.svg?branch=master">](https://travis-ci.org/jgallagher/rusqlite)


### Data structures

* [bluss/rust-itertools ★254](https://github.com/bluss/rust-itertools) — [<img src="https://travis-ci.org/bluss/rust-itertools.svg?branch=master">](https://travis-ci.org/bluss/rust-itertools)
* [contain-rs](https://github.com/contain-rs) — Extension of Rust's std::collections
* [fizyk20/generic-array ★39](https://github.com/fizyk20/generic-array) – a hack to allow for arrays sized by typenums [<img src="https://travis-ci.org/fizyk20/generic-array.svg?branch=master">](https://travis-ci.org/fizyk20/generic-array)
* [Nemo157/roaring-rs ★49](https://github.com/Nemo157/roaring-rs) – Roaring Bitmaps in Rust [<img src="https://travis-ci.org/Nemo157/roaring-rs.svg?branch=master">](https://travis-ci.org/Nemo157/roaring-rs)
* [reem/rust-typemap ★64](https://github.com/reem/rust-typemap) — [<img src="https://travis-ci.org/reem/rust-typemap.svg?branch=master">](https://travis-ci.org/reem/rust-typemap)
* [serde-rs/serde ★896](https://github.com/serde-rs/serde) — a framework to generically serialize Rust data structures [<img src="https://api.travis-ci.org/serde-rs/serde.svg?branch=master">](https://travis-ci.org/serde-rs/serde)


### Date and time

[[date](https://crates.io/keywords/date), [time](https://crates.io/keywords/time)]

* [chronotope/chrono ★304](https://github.com/chronotope/chrono) — [<img src="https://travis-ci.org/chronotope/chrono.svg?branch=master">](https://travis-ci.org/chronotope/chrono)
* [yaa110/rust-persian-calendar ★1](https://github.com/yaa110/rust-persian-calendar) — [<img src="https://travis-ci.org/yaa110/rust-persian-calendar.svg?branch=master">](https://travis-ci.org/yaa110/rust-persian-calendar)


### Distributed Systems

* Apache Kafka
  * [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka) [[rdkafka](https://crates.io/crates/rdkafka)] — [librdkafka ★1031](https://github.com/edenhill/librdkafka) bindings [<img src="https://travis-ci.org/fede1024/rust-rdkafka.svg?branch=master">](https://travis-ci.org/fede1024/rust-rdkafka)
  * [spicavigo/kafka-rust ★169](https://github.com/spicavigo/kafka-rust) — [<img src="https://travis-ci.org/spicavigo/kafka-rust.svg?branch=master">](https://travis-ci.org/spicavigo/kafka-rust)
* Beanstalkd
  * [schickling/rust-beanstalkd](https://github.com/schickling/rust-beanstalkd) — [Beanstalkd ★3847](https://github.com/kr/beanstalkd) bindings [<img src="https://travis-ci.org/schickling/rust-beanstalkd.svg?branch=master">](https://travis-ci.org/schickling/rust-beanstalkd)
* HDFS
  * [hyunsik/hdfs-rs ★17 ⏳1Y](https://github.com/hyunsik/hdfs-rs) — libhdfs bindings [<img src="https://travis-ci.org/hyunsik/hdfs-rs.svg?branch=master">](https://travis-ci.org/hyunsik/hdfs-rs)


### Email

[[email](https://crates.io/keywords/email), [imap](https://crates.io/keywords/imap), [smtp](https://crates.io/keywords/smtp)]

* [gsquire/sendgrid-rs ★9](https://github.com/gsquire/sendgrid-rs) — unofficial Rust library for SendGrid API [<img src="https://travis-ci.org/gsquire/sendgrid-rs.svg?branch=master">](https://travis-ci.org/gsquire/sendgrid-rs)
* [lettre/lettre ★146](https://github.com/lettre/lettre) — an SMTP-library for Rust [<img src="https://travis-ci.org/lettre/lettre.svg?branch=master">](https://travis-ci.org/lettre/lettre)
* [staktrace/mailparse ★16](https://github.com/staktrace/mailparse) [[mailparse](https://crates.io/crates/mailparse)] — a library for parsing real-world email files [<img src="https://travis-ci.org/staktrace/mailparse.svg?branch=master">](https://travis-ci.org/staktrace/mailparse)

### Encoding

[[encoding](https://crates.io/keywords/encoding)]

* ASN.1
  * [alex/rust-asn1](https://github.com/alex/rust-asn1) — a Rust ASN.1 (DER) serializer [<img src="https://travis-ci.org/alex/rust-asn1.svg?branch=master">](https://travis-ci.org/alex/rust-asn1)
* Bencode
  * [arjantop/rust-bencode ★19](https://github.com/arjantop/rust-bencode) — [Bencode](https://en.wikipedia.org/wiki/Bencode) implementation in Rust [<img src="https://travis-ci.org/arjantop/rust-bencode.svg?branch=master">](https://travis-ci.org/arjantop/rust-bencode)
* Binary
  * [arcnmx/nue ★30 ⏳1Y](https://github.com/arcnmx/nue) — I/O and binary data encoding for Rust [<img src="https://travis-ci.org/arcnmx/nue.svg?branch=master">](https://travis-ci.org/arcnmx/nue)
  * [TyOverby/bincode ★208](https://github.com/TyOverby/bincode) — a binary encoder/decoder in Rust [<img src="https://travis-ci.org/TyOverby/bincode.svg?branch=master">](https://travis-ci.org/TyOverby/bincode)
* BSON
  * [zonyitoo/bson-rs ★40](https://github.com/zonyitoo/bson-rs) — [<img src="https://travis-ci.org/zonyitoo/bson-rs.svg?branch=master">](https://travis-ci.org/zonyitoo/bson-rs)
* Byte swapping
  * [BurntSushi/byteorder ★174](https://github.com/BurntSushi/byteorder) — Supports big-endian, little-endian and native byte orders [<img src="https://travis-ci.org/BurntSushi/byteorder.svg?branch=master">](https://travis-ci.org/BurntSushi/byteorder)
* Cap'n Proto
  * [dwrensha/capnproto-rust ★422](https://github.com/dwrensha/capnproto-rust) — [<img src="https://travis-ci.org/dwrensha/capnproto-rust.svg?branch=master">](https://travis-ci.org/dwrensha/capnproto-rust)
* CBOR
  * [BurntSushi/rust-cbor ★51](https://github.com/BurntSushi/rust-cbor) — Supports JSON conversion and type-based encoding/decoding [<img src="https://travis-ci.org/BurntSushi/rust-cbor.svg?branch=master">](https://travis-ci.org/BurntSushi/rust-cbor)
* Character Encoding
  * [lifthrasiir/rust-encoding ★128](https://github.com/lifthrasiir/rust-encoding) — [<img src="https://travis-ci.org/lifthrasiir/rust-encoding.svg?branch=master">](https://travis-ci.org/lifthrasiir/rust-encoding)
* CRC
  * [mrhooray/crc-rs ★15](https://github.com/mrhooray/crc-rs) — [<img src="https://travis-ci.org/mrhooray/crc-rs.svg?branch=master">](https://travis-ci.org/mrhooray/crc-rs)
* CSV
  * [BurntSushi/rust-csv ★262](https://github.com/BurntSushi/rust-csv) — [<img src="https://travis-ci.org/BurntSushi/rust-csv.svg?branch=master">](https://travis-ci.org/BurntSushi/rust-csv)
* HTML
  * [servo/html5ever ★425](https://github.com/servo/html5ever) — High-performance browser-grade HTML5 parser [<img src="https://travis-ci.org/servo/html5ever.svg?branch=master">](https://travis-ci.org/servo/html5ever)
  * [veddan/rust-htmlescape ★11](https://github.com/veddan/rust-htmlescape) — encoding/decoding HTML entities [<img src="https://travis-ci.org/veddan/rust-htmlescape.svg?branch=master">](https://travis-ci.org/veddan/rust-htmlescape)
* JSON
  * [serde-rs/json](https://github.com/serde-rs/json) [[serde\_json](https://crates.io/crates/serde_json)] — JSON support for [Serde ★896](https://github.com/serde-rs/serde) framework [<img src="https://travis-ci.org/serde-rs/json.svg?branch=master">](https://travis-ci.org/serde-rs/json)
  * [maciejhirsz/json-rust ★181](https://github.com/maciejhirsz/json-rust) [[json](https://crates.io/crates/json)] — JSON implementation in Rust [<img src="https://travis-ci.org/maciejhirsz/json-rust.svg?branch=master">](https://travis-ci.org/maciejhirsz/json-rust)
* Jsonnet
  * [Qihoo360/rust-jsonnet ★20 ⏳1Y](https://github.com/Qihoo360/rust-jsonnet) —  [<img src="https://travis-ci.org/Qihoo360/rust-jsonnet.svg?branch=master">](https://travis-ci.org/Qihoo360/rust-jsonnet)
* MsgPack
  * [mneumann/rust-msgpack ★114 ⏳1Y](https://github.com/mneumann/rust-msgpack) — [<img src="https://travis-ci.org/mneumann/rust-msgpack.svg?branch=master">](https://travis-ci.org/mneumann/rust-msgpack)
  * [3Hren/msgpack-rust ★188](https://github.com/3Hren/msgpack-rust) — a pure Rust low/high level MessagePack implementation [<img src="https://travis-ci.org/3Hren/msgpack-rust.svg?branch=master">](https://travis-ci.org/3Hren/msgpack-rust)
* ProtocolBuffers
  * [stepancheg/rust-protobuf ★441](https://github.com/stepancheg/rust-protobuf) — [<img src="https://travis-ci.org/stepancheg/rust-protobuf.svg?branch=master">](https://travis-ci.org/stepancheg/rust-protobuf)
* RON (Rusty Object Notation)
  * [kvark/ron ★74 ⏳2Y](https://github.com/kvark/ron) — [<img src="https://travis-ci.org/kvark/ron.svg?branch=master">](https://travis-ci.org/kvark/ron)
* Tnetstring
  * [erickt/rust-tnetstring ★13 ⏳2Y](https://github.com/erickt/rust-tnetstring) — [<img src="https://travis-ci.org/erickt/rust-tnetstring.svg?branch=master">](https://travis-ci.org/erickt/rust-tnetstring)
* TOML
  * [alexcrichton/toml-rs ★241](https://github.com/alexcrichton/toml-rs) — [<img src="https://travis-ci.org/alexcrichton/toml-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/toml-rs)
* XML
  * [Florob/RustyXML ★62 ⏳1Y](https://github.com/Florob/RustyXML) — an XML parser written in Rust [<img src="https://travis-ci.org/Florob/RustyXML.svg?branch=master">](https://travis-ci.org/Florob/RustyXML)
  * [shepmaster/sxd-document ★62](https://github.com/shepmaster/sxd-document) — An XML library in Rust [<img src="https://travis-ci.org/shepmaster/sxd-document.svg?branch=master">](https://travis-ci.org/shepmaster/sxd-document)
  * [shepmaster/sxd-xpath ★35](https://github.com/shepmaster/sxd-xpath) — An XPath library in Rust [<img src="https://travis-ci.org/shepmaster/sxd-xpath.svg?branch=master">](https://travis-ci.org/shepmaster/sxd-xpath)
  * [netvl/xml-rs ★152](https://github.com/netvl/xml-rs) — a streaming XML library [<img src="https://travis-ci.org/netvl/xml-rs.svg?branch=master">](https://travis-ci.org/netvl/xml-rs)
* YAML
  * [chyh1990/yaml-rust ★140](https://github.com/chyh1990/yaml-rust) — The missing YAML 1.2 implementation for Rust. [<img src="https://travis-ci.org/chyh1990/yaml-rust.svg?branch=master">](https://travis-ci.org/chyh1990/yaml-rust)
  * [dtolnay/serde-yaml](https://github.com/dtolnay/serde-yaml) [[serde\_yaml](https://crates.io/crates/serde_yaml)] — YAML support for [Serde ★896](https://github.com/serde-rs/serde) framework [<img src="https://travis-ci.org/dtolnay/serde-yaml.svg?branch=master">](https://travis-ci.org/dtolnay/serde-yaml)
  * [kimhyunkang/libyaml-rust ★17](https://github.com/kimhyunkang/libyaml-rust) — [libyaml](http://pyyaml.org/wiki/LibYAML) bindings [<img src="https://travis-ci.org/kimhyunkang/libyaml-rust.svg?branch=master">](https://travis-ci.org/kimhyunkang/libyaml-rust)

### Filesystem

[[filesystem](https://crates.io/keywords/filesystem)]
* Operations
  * [webdesus/fs_extra ★7](https://github.com/webdesus/fs_extra) — expanding opportunities standard library std::fs and std::io [<img src="https://travis-ci.org/webdesus/fs_extra.svg?branch=master">](https://travis-ci.org/webdesus/fs_extra)
* Temporary Files
  * [rust-lang-nursery/tempdir ★52](https://github.com/rust-lang-nursery/tempdir) — temporary directory library [<img src="https://travis-ci.org/rust-lang-nursery/tempdir.svg?branch=master">](https://travis-ci.org/rust-lang-nursery/tempdir)
  * [Stebalien/tempfile ★35](https://github.com/Stebalien/tempfile) — temporary file library [<img src="https://travis-ci.org/Stebalien/tempfile.svg?branch=master">](https://travis-ci.org/Stebalien/tempfile)
  * [Stebalien/xattr ★2](https://github.com/Stebalien/xattr) [[xattr](https://crates.io/crates/xattr)] — list and manipulate unix extended file attributes [<img src="https://travis-ci.org/Stebalien/xattr.svg?branch=master">](https://travis-ci.org/Stebalien/xattr)

### Game development

([AreWeGameYet](http://arewegameyet.com))
* Allegro
  * [SiegeLord/RustAllegro ★37](https://github.com/SiegeLord/RustAllegro) — [Allegro 5](http://liballeg.org/) bindings [<img src="https://travis-ci.org/SiegeLord/RustAllegro.svg?branch=master">](https://travis-ci.org/SiegeLord/RustAllegro)
* Challonge
  * [vityafx/challonge-rs ★0](https://github.com/vityafx/challonge-rs) [[challonge](https://crates.io/crates/challonge)] — Client library for the Challonge REST API. Helps to organize tournaments. [<img src="https://travis-ci.org/vityafx/challonge-rs.svg?branch=master">](https://travis-ci.org/vityafx/challonge-rs)
* Corange
  * [lucidscape/corange-rs](https://github.com/lucidscape/corange-rs) — [Corange ★599](https://github.com/orangeduck/Corange) bindings
* Entity-Component Systems (ECS)
  * [slide-rs/specs ★280](https://github.com/slide-rs/specs) — Specs Parallel ECS [<img src="https://travis-ci.org/slide-rs/specs.svg">](httpsL//github.com/travis-ci.org/slide-rs/specs)
* Game Engines
  * [Amethyst](https://www.amethyst.rs) — Data-oriented game engine [<img src="https://travis-ci.org/amethyst/amethyst.svg?branch=master">](https://travis-ci.org/amethyst/amethyst)
  * [Piston](http://www.piston.rs) — [<img src="https://travis-ci.org/PistonDevelopers/piston.svg?branch=master">](https://travis-ci.org/PistonDevelopers/piston)
* SDL [[sdl](https://crates.io/keywords/sdl)]
  * [brson/rust-sdl ★163 ⏳1Y](https://github.com/brson/rust-sdl) — [SDL1](http://www.libsdl.org/) bindings [<img src="https://travis-ci.org/brson/rust-sdl.svg?branch=master">](https://travis-ci.org/brson/rust-sdl)
  * [AngryLawyer/rust-sdl2 ★496](https://github.com/AngryLawyer/rust-sdl2) — [SDL2](http://www.libsdl.org/) bindings [<img src="https://travis-ci.org/AngryLawyer/rust-sdl2.svg?branch=master">](https://travis-ci.org/AngryLawyer/rust-sdl2)
* SFML
  * [jeremyletang/rust-sfml ★243](https://github.com/jeremyletang/rust-sfml) — [SFML](http://www.sfml-dev.org/) bindings [<img src="https://travis-ci.org/jeremyletang/rust-sfml.svg?branch=master">](https://travis-ci.org/jeremyletang/rust-sfml)
* Voxlap
  * [bbodi/rust-voxlap ★10 ⏳2Y](https://github.com/bbodi/rust-voxlap) — [Voxlap](http://advsys.net/ken/voxlap.htm) bindings

### Geospatial

[[geo](https://crates.io/keywords/geo), [gis](https://crates.io/keywords/gis)]

* [Georust](https://github.com/georust) — geospatial tools and libraries written in Rust
* [rust-reverse-geocoder ★15](https://github.com/llambda/rust-reverse-geocoder) — a fast, offline reverse geocoder in Rust, inspired by https://github.com/thampiman/reverse-geocoder

### Graphics

[[graphics](https://crates.io/keywords/graphics)]

* [gfx-rs/gfx ★926](https://github.com/gfx-rs/gfx) — A high-performance, bindless graphics API for Rust. [<img src="https://img.shields.io/travis/gfx-rs/gfx/master.svg">](https://travis-ci.org/gfx-rs/gfx)
* Font
  * [dylanede/rusttype ★277](https://github.com/dylanede/rusttype) — a pure Rust alternative to libraries like FreeType [<img src="https://img.shields.io/travis/dylanede/rusttype/master.svg">](https://travis-ci.org/dylanede/rusttype)
* OpenGL [[opengl](https://crates.io/keywords/opengl)]
  * [brendanzab/gl-rs ★240](https://github.com/brendanzab/gl-rs) — [<img src="https://travis-ci.org/brendanzab/gl-rs.svg?branch=master">](https://travis-ci.org/brendanzab/gl-rs)
  * [PistonDevelopers/glfw-rs ★231](https://github.com/PistonDevelopers/glfw-rs) — [<img src="https://travis-ci.org/PistonDevelopers/glfw-rs.svg?branch=master">](https://travis-ci.org/PistonDevelopers/glfw-rs)
  * [tomaka/glium ★1266](https://github.com/tomaka/glium) — safe OpenGL wrapper for the Rust language. [<img src="https://travis-ci.org/tomaka/glium.svg?branch=master">](https://travis-ci.org/tomaka/glium)
  * [tomaka/glutin ★644](https://github.com/tomaka/glutin) — Rust alternative to [GLFW](http://www.glfw.org/) [<img src="https://travis-ci.org/tomaka/glutin.svg?branch=master">](https://travis-ci.org/tomaka/glutin)
* PDF
  * [kaj/rust-pdf ★21](https://github.com/kaj/rust-pdf) — [<img src="https://travis-ci.org/kaj/rust-pdf.svg?branch=master">](https://travis-ci.org/kaj/rust-pdf)
* [Vulkan](https://www.khronos.org/vulkan/) [[vulkan](https://crates.io/keywords/vulkan)]
  * [tomaka/vulkano ★728](https://github.com/tomaka/vulkano) [[vulkano](https://crates.io/crates/vulkano)] — [<img src="https://travis-ci.org/tomaka/vulkano.svg?branch=master">](https://travis-ci.org/tomaka/vulkano)


### Graph processing

* [kud1ing/tinkerpop-rs ★3](https://github.com/kud1ing/tinkerpop-rs) — an example how to use Apache TinkerPop from Rust [<img src="https://travis-ci.org/kud1ing/tinkerpop-rs.svg?branch=master">](https://travis-ci.org/kud1ing/tinkerpop-rs)


### GUI

[[gui](https://crates.io/keywords/gui)]

* [PistonDevelopers/conrod ★1083](https://github.com/PistonDevelopers/conrod) — An easy-to-use, immediate-mode, 2D GUI library written entirely in Rust [<img src="https://travis-ci.org/PistonDevelopers/conrod.svg?branch=master">](https://travis-ci.org/PistonDevelopers/conrod)
* Cocoa
  * [kylewlacy/sorbet-cocoa ★23](https://github.com/kylewlacy/sorbet-cocoa) — [<img src="https://travis-ci.org/kylewlacy/sorbet-cocoa.svg?branch=master">](https://travis-ci.org/kylewlacy/sorbet-cocoa)
  * [servo/cocoa-rs ★232](https://github.com/servo/cocoa-rs)
* [GTK+](http://www.gtk.org) [[gtk](https://crates.io/keywords/gtk)]
  * [gtk-rs/gtk ★487](https://github.com/gtk-rs/gtk) — GTK+ bindings [<img src="https://travis-ci.org/gtk-rs/gtk.svg?branch=master">](https://travis-ci.org/gtk-rs/gtk)
* [gyscos/Cursive ★273](https://github.com/gyscos/Cursive) [[cursive](https://crates.io/crates/cursive)] — [<img src="https://travis-ci.org/gyscos/Cursive.svg?branch=master">](https://travis-ci.org/gyscos/Cursive)
* [ImGui ★6614](https://github.com/ocornut/imgui)
  * [imgui-rs ★177](https://github.com/Gekkio/imgui-rs) — Rust bindings for ImGui [<img src="https://travis-ci.org/Gekkio/imgui-rs.svg?branch=master">](https://travis-ci.org/Gekkio/imgui-rs)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
  * [dcampbell24/iup-rust ★24 ⏳1Y](https://github.com/dcampbell24/iup-rust) — IUP bindings [<img src="https://travis-ci.org/dcampbell24/iup-rust.svg?branch=master">](https://travis-ci.org/dcampbell24/iup-rust)
  * [Kiss-ui ★284](https://github.com/KISS-UI/kiss-ui) — a simple UI framework built on IUP [![Build Status](https://travis-ci.org/cybergeek94/kiss-ui.svg?branch=master)](https://travis-ci.org/cybergeek94/kiss-ui)
* [libui ★4293](https://github.com/andlabs/libui)
  * [pcwalton/libui-rs ★139](https://github.com/pcwalton/libui-rs) — libui bindings [<img src="https://travis-ci.org/pcwalton/libui-rs.svg?branch=master">](https://travis-ci.org/pcwalton/libui-rs)
* [ncurses](http://www.gnu.org/software/ncurses/) [[ncurses](https://crates.io/keywords/ncurses)]
  * [jeaye/ncurses-rs ★257](https://github.com/jeaye/ncurses-rs) — ncurses bindings [<img src="https://travis-ci.org/jeaye/ncurses-rs.svg?branch=master">](https://travis-ci.org/jeaye/ncurses-rs)
* [Nuklear ★6416](https://github.com/vurtun/nuklear)
  * [nuklear-rust ★37](https://github.com/snuk182/nuklear-rust) — Rust bindings for Nuklear [<img src="https://travis-ci.org/snuk182/nuklear-rust.svg?branch=master">](https://travis-ci.org/snuk182/nuklear-rust)
* [Qt](http://doc.qt.io)
  * [cyndis/qmlrs ★355 ⏳1Y](https://github.com/cyndis/qmlrs) — QtQuick bindings [<img src="https://travis-ci.org/cyndis/qmlrs.svg?branch=master">](https://travis-ci.org/cyndis/qmlrs)
  * [kitech/qt.rs ★22 ⏳1Y](https://github.com/kitech/qt.rs) — Qt5 bindings [<img src="https://travis-ci.org/kitech/qt.rs.svg?branch=master">](https://travis-ci.org/kitech/qt.rs)
  * [rust-qt](https://github.com/rust-qt) —
  * [White-Oak/qml-rust ★93](https://github.com/White-Oak/qml-rust) — QML bindings. [<img src="https://travis-ci.org/White-Oak/qml-rust.svg?branch=master">](https://travis-ci.org/White-Oak/qml-rust)
* [saurvs/nfd-rs](https://github.com/saurvs/nfd-rs) — [nativefiledialog ★388](https://github.com/mlabbe/nativefiledialog) bindings
* [Sciter](http://sciter.com/)
  * [pravic/rust-sciter](https://github.com/pravic/rust-sciter) — Sciter bindings [<img src="https://ci.appveyor.com/api/projects/status/github/pravic/rust-sciter?svg=true">](https://ci.appveyor.com/project/pravic/rust-sciter)
* [Termbox ★1018](https://github.com/nsf/termbox)
  * [gchp/rustbox ★262](https://github.com/gchp/rustbox) — a Rust implementation of Termbox [<img src="https://travis-ci.org/gchp/rustbox.svg?branch=master">](https://travis-ci.org/gchp/rustbox)


### Image processing

* [chyh1990/imageproc ★57 ⏳1Y](https://github.com/chyh1990/imageproc) — An advanced image processing library for Rust. [![Build Status](https://travis-ci.org/chyh1990/imageproc.svg?branch=master)](https://travis-ci.org/chyh1990/imageproc)
* [cybergeek94/img-hash](https://github.com/cybergeek94/img_hash) — Perceptual image hashing and comparison for equality and similarity.
* [PistonDevelopers/image ★469](https://github.com/PistonDevelopers/image) — Basic imaging processing functions and methods for converting to and from image formats [<img src="https://travis-ci.org/PistonDevelopers/image.svg?branch=master">](https://travis-ci.org/PistonDevelopers/image)


### Logging

[[log](https://crates.io/keywords/log)]

* [rust-lang-nursery/log ★181](https://github.com/rust-lang-nursery/log) — Logging implementation for Rust [![Build Status](https://travis-ci.org/rust-lang-nursery/log.svg?branch=master)](https://travis-ci.org/rust-lang-nursery/log)
* [slog-rs/slog ★331](https://github.com/slog-rs/slog) — Structured, composable logging for Rust [![Build Status](https://travis-ci.org/slog-rs/slog.svg?branch=master)](https://travis-ci.org/slog-rs/slog)
* [sfackler/log4rs ★104](https://github.com/sfackler/log4rs) — highly configurable logging framework modeled after Java's Logback and log4j libraries [![Build Status](https://travis-ci.org/sfackler/log4rs.svg?branch=master)](https://travis-ci.org/sfackler/log4rs)


### Machine learning

[[machine learning](https://crates.io/keywords/machine-learning)]

See also [About Rust’s Machine Learning Community](https://medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790#.hvkp56j3f).

* [AtheMathmo/rusty-machine ★411](https://github.com/AtheMathmo/rusty-machine) — Machine learning library for Rust [![Build Status](https://travis-ci.org/AtheMathmo/rusty-machine.svg?branch=master)](https://travis-ci.org/AtheMathmo/rusty-machine)
* [autumnai/leaf ★4825](https://github.com/autumnai/leaf) — Open Machine Intelligence framework. [![Build Status](https://travis-ci.org/autumnai/leaf.svg?branch=master)](https://travis-ci.org/autumnai/leaf)
* [tensorflow/rust ★625](https://github.com/tensorflow/rust) — Rust language bindings for TensorFlow. [![Build Status](https://travis-ci.org/tensorflow/rust.svg?branch=master)](https://travis-ci.org/tensorflow/rust)
* [maciejkula/rustlearn ★210](https://github.com/maciejkula/rustlearn) — Machine learning crate for Rust. [![Circle CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://circleci.com/gh/maciejkula/rustlearn)


### Markup language

* CommonMark
  * [google/pulldown-cmark ★320](https://github.com/google/pulldown-cmark) — [CommonMark](http://commonmark.org/) parser in Rust


### Mobile

[Geal/rust_on_mobile ★37](https://github.com/Geal/rust_on_mobile)

* Android
  * [tomaka/android-rs-glue ★413](https://github.com/tomaka/android-rs-glue) — glue between Rust and Android [<img src="https://travis-ci.org/tomaka/android-rs-glue.svg?branch=master">](https://travis-ci.org/tomaka/android-rs-glue)
* iOS
  * [TimNN/cargo-lipo ★32](https://github.com/TimNN/cargo-lipo) — a cargo lipo subcommand which automatically creates a universal library for use with your iOS application. [<img src="https://travis-ci.org/TimNN/cargo-lipo.svg?branch=master">](https://travis-ci.org/TimNN/cargo-lipo)
  * [vhbit/ObjCrust ★36 ⏳1Y](https://github.com/vhbit/ObjCrust) — using Rust to create an iOS static library [<img src="https://travis-ci.org/vhbit/ObjCrust.svg?branch=master">](https://travis-ci.org/vhbit/ObjCrust)
* Pebble
  * [andars/pebble.rs ★39 ⏳1Y](https://github.com/andars/pebble.rs) — a crate that allows Rust to be used to develop Pebble applications.


### Network programming

* FTP
  * [mattnenterprise/rust-ftp ★36](https://github.com/mattnenterprise/rust-ftp) — an [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol) client for Rust [<img src="https://travis-ci.org/mattnenterprise/rust-ftp.svg?branch=master">](https://travis-ci.org/mattnenterprise/rust-ftp)
* Low level
  * [libpnet/libpnet ★461](https://github.com/libpnet/libpnet) — a cross-platform, low level networking [<img src="https://travis-ci.org/libpnet/libpnet.svg?branch=master">](https://travis-ci.org/libpnet/libpnet)
  * [tokio-rs/tokio ★622](https://github.com/tokio-rs/tokio) — a network application framework for rapid development and highly scalable production deployments of clients and servers.
  * [dylanmckay/protocol ★12](https://github.com/dylanmckay/protocol) — Custom TCP/UDP protocol definitions
* NanoMsg
  * [thehydroimpulse/nanomsg.rs ★227](https://github.com/thehydroimpulse/nanomsg.rs) — [nanomsg](http://nanomsg.org/) bindings [<img src="https://travis-ci.org/thehydroimpulse/nanomsg.rs.svg?branch=master">](https://travis-ci.org/thehydroimpulse/nanomsg.rs)
* NNTP
  * [mattnenterprise/rust-nntp ★8 ⏳1Y](https://github.com/mattnenterprise/rust-nntp) — an [NNTP](https://en.wikipedia.org/wiki/Network_News_Transfer_Protocol) client for Rust [<img src="https://travis-ci.org/mattnenterprise/rust-nntp.svg?branch=master">](https://travis-ci.org/mattnenterprise/rust-nntp)
* POP3
  * [mattnenterprise/rust-pop3 ★8](https://github.com/mattnenterprise/rust-pop3) — a [POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol) client for Rust [<img src="https://travis-ci.org/mattnenterprise/rust-pop3.svg?branch=master">](https://travis-ci.org/mattnenterprise/rust-pop3)
* SSH
  * [alexcrichton/ssh2-rs ★73](https://github.com/alexcrichton/ssh2-rs) — [libssh2](http://www.libssh2.org/) bindings [<img src="https://travis-ci.org/alexcrichton/ssh2-rs.svg?branch=master">](https://travis-ci.org/alexcrichton/ssh2-rs)
  * [Thrussh](http://pijul.org/thrussh/) — an SSH library written from scratch in Rust, backed by [libsodium](https://download.libsodium.org/doc/)
* Stomp
  * [zslayton/stomp-rs ★46](https://github.com/zslayton/stomp-rs) — a [STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html) client implementation in Rust [<img src="https://travis-ci.org/zslayton/stomp-rs.svg?branch=master">](https://travis-ci.org/zslayton/stomp-rs)
* uTP
  * [meqif/rust-utp ★60](https://github.com/meqif/rust-utp) — a [uTP](http://www.bittorrent.org/beps/bep_0029.html) (Micro Transport Protocol) library for Rust. [<img src="https://travis-ci.org/meqif/rust-utp.svg?branch=master">](https://travis-ci.org/meqif/rust-utp)
* ZeroMQ
  * [erickt/rust-zmq ★238](https://github.com/erickt/rust-zmq) — [ZeroMQ](http://zeromq.org/) bindings [<img src="https://travis-ci.org/erickt/rust-zmq.svg?branch=master">](https://travis-ci.org/erickt/rust-zmq)


### Parser

  * [dragostis/pest](https://github.com/dragostis/pest) — Elegant, efficient grammars [![Build Status](https://travis-ci.org/dragostis/pest.svg?branch=master)]
(https://travis-ci.org/dragostis/pest)
  * [Geal/nom ★1321](https://github.com/Geal/nom) — parser combinator library [<img src="https://travis-ci.org/Geal/nom.svg?branch=master">](https://travis-ci.org/Geal/nom)
  * [ivanceras/inquerest ★17](https://github.com/ivanceras/inquerest) — an URL parameter parser for rest filter inquiry [![Build Status](https://travis-ci.org/ivanceras/inquerest.svg?branch=master)](https://travis-ci.org/ivanceras/inquerest)
  * [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) — Parsing Expression Grammar (PEG) parser generator
  * [m4rw3r/chomp ★144](https://github.com/m4rw3r/chomp) – A fast monadic-style parser combinator [<img src="https://travis-ci.org/m4rw3r/chomp.svg?branch=master">](https://travis-ci.org/m4rw3r/chomp)
  * [Marwes/combine ★288](https://github.com/Marwes/combine) — parser combinator library [<img src="https://travis-ci.org/Marwes/combine.svg?branch=master">](https://travis-ci.org/Marwes/combine)
  * [nikomatsakis/lalrpop](https://github.com/nikomatsakis/lalrpop) — LR(1) parser generator for Rust [![Build status](https://travis-ci.org/nikomatsakis/lalrpop.svg?branch=master)](https://travis-ci.org/nikomatsakis/lalrpop)
  * [nrc/zero ★13](https://github.com/nrc/zero) — zero-allocation parsing of binary data [<img src="https://travis-ci.org/nrc/zero.svg?branch=master">](https://travis-ci.org/nrc/zero)
  * [ptal/oak](https://github.com/ptal/oak) — a typed PEG parser generator (compiler plugin)
  * [rustless/queryst ★30](https://github.com/rustless/queryst) — a query string parsing library for Rust inspired by https://github.com/ljharb/qs [![Build Status](https://travis-ci.org/rustless/queryst.svg?branch=master)](https://travis-ci.org/rustless/queryst)


### Platform specific

* Linux
  * [hannobraun/inotify-rs ★46](https://github.com/hannobraun/inotify-rs) — [inotify](https://en.wikipedia.org/wiki/Inotify) bindings [<img src="https://travis-ci.org/hannobraun/inotify-rs.svg?branch=master">](https://travis-ci.org/hannobraun/inotify-rs)
  * [yaa110/rust-iptables ★9](https://github.com/yaa110/rust-iptables) — [iptables](https://www.netfilter.org/projects/iptables/index.html) bindings [<img src="https://travis-ci.org/yaa110/rust-iptables.svg?branch=master">](https://travis-ci.org/yaa110/rust-iptables)
* Unix-like
  * [nix-rust/nix ★459](https://github.com/nix-rust/nix) — Unix-like API bindings [<img src="https://travis-ci.org/nix-rust/nix.svg?branch=master">](https://travis-ci.org/nix-rust/nix)
  * [zargony/rust-fuse](https://github.com/zargony/rust-fuse) — [FUSE ★713](https://github.com/libfuse/libfuse) bindings <img src="https://travis-ci.org/zargony/rust-fuse.svg?branch=master">
* Windows
  * [retep998/winapi-rs ★273](https://github.com/retep998/winapi-rs) — Windows API bindings [<img src="https://travis-ci.org/retep998/winapi-rs.svg?branch=master">](https://travis-ci.org/retep998/winapi-rs)


## Scripting
[[scripting](https://crates.io/keywords/scripting)]
* [PistonDevelopers/dyon ★386](https://github.com/PistonDevelopers/dyon) - A rusty dynamically typed scripting language
* [gluon-lang/gluon ★600](https://github.com/gluon-lang/gluon) -  A small, statically-typed, functional programming language
* [murarth/ketos ★176](https://github.com/murarth/ketos) - A Lisp dialect functional programming language serving as a scripting and extension language for rust


### Template engine

* Handlebars
  * [sunng87/handlebars-rust ★174](https://github.com/sunng87/handlebars-rust) — Handlebars template engine with inheritance, custom helper support. [<img src="https://travis-ci.org/sunng87/handlebars-rust.svg?branch=master">](https://travis-ci.org/sunng87/handlebars-rust)
* HTML
  * [lfairy/maud ★258](https://github.com/lfairy/maud) — compile-time HTML templates [<img src="https://travis-ci.org/lfairy/maud.svg?branch=master">](https://travis-ci.org/lfairy/maud)
  * [Stebalien/horrorshow-rs ★82](https://github.com/Stebalien/horrorshow-rs) — compile-time HTML templates [<img src="https://travis-ci.org/Stebalien/horrorshow-rs.svg?branch=master">](https://travis-ci.org/Stebalien/horrorshow-rs)
  * [kaj/ructe ★24](https://github.com/kaj/ructe) — HTML template system for Rust [<img src="https://travis-ci.org/kaj/ructe.svg?branch=master">](https://travis-ci.org/kaj/ructe)
  * [Keats/tera ★266](https://github.com/Keats/tera) — template engine based on Jinja2 and the Django template language. [<img src="https://travis-ci.org/Keats/tera.svg?branch=master">](https://travis-ci.org/Keats/tera)
  * [djc/askama ★204](https://github.com/djc/askama) — template rendering engine based on Jinja [<img src="https://travis-ci.org/djc/askama.svg?branch=master">](https://travis-ci.org/djc/askama)
* Mustache
  * [rustache/rustache ★165](https://github.com/rustache/rustache) — [<img src="https://travis-ci.org/rustache/rustache.svg?branch=master">](https://travis-ci.org/rustache/rustache)
* [tailhook/marafet ★6 ⏳1Y](https://github.com/tailhook/marafet) — Compiler for Jade-like template language to cito.js-based virtual dom


### Text processing

* [BurntSushi/suffix](https://github.com/BurntSushi/suffix) — Linear time suffix array construction (with Unicode support) [<img src="https://travis-ci.org/BurntSushi/suffix.svg?branch=master">](https://travis-ci.org/BurntSushi/suffix)
* [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter) — Elastic tab stops (i.e., text column alignment) [<img src="https://travis-ci.org/BurntSushi/tabwriter.svg?branch=master">](https://travis-ci.org/BurntSushi/tabwriter)
* [pwoolcoc/ngrams ★8](https://github.com/pwoolcoc/ngrams) — Construct [n-grams](https://en.wikipedia.org/wiki/N-gram) from arbitrary iterators [<img src="https://travis-ci.org/pwoolcoc/ngrams.svg?branch=master">](https://travis-ci.org/pwoolcoc/ngrams)
* [rust-lang-nursery/regex](https://github.com/rust-lang-nursery/regex) — Regular expressions (RE2 style) [<img src="https://travis-ci.org/rust-lang-nursery/regex.svg?branch=master">](https://travis-ci.org/rust-lang-nursery/regex)


### Text search

* [BurntSushi/fst ★313](https://github.com/BurntSushi/fst) [[fst](https://crates.io/crates/fst)] — [<img src="https://travis-ci.org/BurntSushi/fst.svg?branch=master">](https://travis-ci.org/BurntSushi/fst)
* [JDemler/perlin ★40](https://github.com/JDemler/perlin) [[perlin](https://crates.io/crates/perlin)] — [<img src="https://travis-ci.org/JDemler/perlin.svg?branch=master">](https://travis-ci.org/JDemler/perlin)
* [tantivy-search/tantivy ★317](https://github.com/tantivy-search/tantivy) [[tantivy](https://crates.io/crates/tantivy)] — [<img src="https://travis-ci.org/tantivy-search/tantivy.svg?branch=master">](https://travis-ci.org/tantivy-search/tantivy)


### Virtualization

* [beneills/quantum ★20](https://github.com/beneills/quantum) — Advanced Rust quantum computer simulator [<img src="https://travis-ci.org/beneills/quantum.svg?branch=master">](https://travis-ci.org/beneills/quantum)
* [ekse/unicorn-rs ★19](https://github.com/ekse/unicorn-rs) — Rust bindings for the unicorn CPU emulator
* [saurvs/hypervisor-rs ★10](https://github.com/saurvs/hypervisor-rs) — Hardware-accelerated virtualization on OS X


### Web programming

See also [Rust web framework comparison ★408](https://github.com/flosse/rust-web-framework-comparison).

* HTTP Client
  * [alexcrichton/curl-rust ★303](https://github.com/alexcrichton/curl-rust) — [libcurl](http://curl.haxx.se/libcurl/) bindings [<img src="https://travis-ci.org/alexcrichton/curl-rust.svg?branch=master">](https://travis-ci.org/alexcrichton/curl-rust)
  * [hyperium/hyper ★2488](https://github.com/hyperium/hyper) — an HTTP implementation [<img src="https://travis-ci.org/hyperium/hyper.svg?branch=master">](https://travis-ci.org/hyperium/hyper)
  * [seanmonstar/reqwest ★217](https://github.com/seanmonstar/reqwest) — an ergonomic HTTP Client for Rust. [<img src="https://travis-ci.org/seanmonstar/reqwest.svg?branch=master">](https://travis-ci.org/seanmonstar/reqwest)
* HTTP Server
  * [fengsp/pencil ★807](https://github.com/fengsp/pencil) — [<img src="https://travis-ci.org/fengsp/pencil.svg?branch=master">](https://travis-ci.org/fengsp/pencil)
  * [hyperium/hyper ★2488](https://github.com/hyperium/hyper) — an HTTP implementation [<img src="https://travis-ci.org/hyperium/hyper.svg?branch=master">](https://travis-ci.org/hyperium/hyper)
  * [Iron ★4025](https://github.com/iron/iron) — a middleware-based server framework [<img src="https://travis-ci.org/iron/iron.svg?branch=master">](https://travis-ci.org/iron/iron)
    * [sunng87/handlebars-iron](https://github.com/sunng87/handlebars-iron) — [Handlebars-rust ★174](https://github.com/sunng87/handlebars-rust) as an Iron web framework middleware. [<img src="https://travis-ci.org/sunng87/handlebars-iron.svg?branch=master">](https://travis-ci.org/sunng87/handlebars-iron)
  * [Nickel ★1848](https://github.com/nickel-org/nickel.rs) — inspired by [Express](http://expressjs.com/) [<img src="https://travis-ci.org/nickel-org/nickel.rs.svg?branch=master">](https://travis-ci.org/nickel-org/nickel.rs)
  * [Ogeon/rustful ★797](https://github.com/Ogeon/rustful) — a RESTful web framework for Rust  [<img src="https://travis-ci.org/Ogeon/rustful.svg?branch=master">](https://travis-ci.org/Ogeon/rustful)
  * [Rocket](https://github.com/SergioBenitez/Rocket) — Rocket is web framework for Rust (nightly) with a focus on ease-of-use, expressability, and speed [<img src="https://travis-ci.org/SergioBenitez/Rocket.svg?branch=master">](https://travis-ci.org/SergioBenitez/Rocket)
  * [Rustless](https://github.com/rustless/rustless) — a REST-like API micro-framework inspired by [Grape](https://github.com/ruby-grape/grape) and [Hyper ★2488](https://github.com/hyperium/hyper) [<img src="https://travis-ci.org/rustless/rustless.svg?branch=master">](https://travis-ci.org/rustless/rustless)
  * [tiny-http](https://github.com/frewsxcv/tiny-http) — Low level HTTP server library [<img src="https://travis-ci.org/frewsxcv/tiny-http.svg?branch=master">](https://travis-ci.org/frewsxcv/tiny-http)
  * [tomaka/rouille ★201](https://github.com/tomaka/rouille) — Web framework in Rust[<img src="https://travis-ci.org/tomaka/rouille.svg?branch=master">](https://travis-ci.org/tomaka/rouille)
  * [sappworks/sapper ★350](https://github.com/sappworks/sapper) — A lightweight web framework built on async hyper, implemented in Rust language. [<img src="https://travis-ci.org/sappworks/sapper.svg?branch=master">](https://travis-ci.org/tomaka/rouille)
* [WebSocket](https://datatracker.ietf.org/doc/rfc6455/)
  * [cyderize/rust-websocket](https://github.com/cyderize/rust-websocket) — a framework for dealing with WebSocket connections (both clients and servers) [<img src="https://travis-ci.org/cyderize/rust-websocket.svg?branch=master">](https://travis-ci.org/cyderize/rust-websocket)
  * [vityafx/urlshortener-rs ★2](https://github.com/vityafx/urlshortener-rs) [[urlshortener](https://crates.io/crates/urlshortener)] — A very simple urlshortener library for Rust. [<img src="https://travis-ci.org/vityafx/urlshortener-rs.svg?branch=master">](https://travis-ci.org/vityafx/urlshortener-rs)
  * [housleyjk/ws-rs ★344](https://github.com/housleyjk/ws-rs) — lightweight, event-driven WebSockets for Rust [<img src="https://travis-ci.org/housleyjk/ws-rs.svg?branch=stable">](https://travis-ci.org/housleyjk/ws-rs)
  * [snapview/tungstenite-rs ★25](https://github.com/snapview/tungstenite-rs) - Lightweight stream-based WebSocket implementation for Rust.
* Miscellaneous
  * [doublifyapis/toolkit-rust ★4](https://github.com/doublifyapis/toolkit-rust) - Doublify API toolkit for Rust [<img src="https://travis-ci.org/doublifyapis/toolkit-rust.svg?branch=master">](https://travis-ci.org/doublifyapis/toolkit-rust)


## Resources

* Benchmarks
  * [TeXitoi/benchmarksgame-rs ★30](https://github.com/TeXitoi/benchmarksgame-rs) — Rust implementations for the [The Computer Language Benchmarks Game](http://benchmarksgame.alioth.debian.org/) [<img src="https://travis-ci.org/TeXitoi/benchmarksgame-rs.svg?branch=master">](https://travis-ci.org/TeXitoi/benchmarksgame-rs)
* Decks & Presentations
  * [Learning systems programming with Rust](https://speakerdeck.com/jvns/learning-systems-programming-with-rust) — Presented by [Julia Evans](https://twitter.com/@b0rk) @ Rustconf 2016.
* Learning
  * [exercism.io](http://exercism.io/languages/rust) — programming exercises that help you learn new concepts in Rust.
  * [Learning Rust With Entirely Too Many Linked Lists](http://cglab.ca/~abeinges/blah/too-many-lists/book/) — in-depth exploration of Rust's memory management rules, through implementing a few different types of list structures.
  * [Rust by Example](http://rustbyexample.com/)
  * [rust-learning ★1695](https://github.com/ctjhoa/rust-learning) — a collection of useful resources to learn Rust
  * [Rustlings ★1709](https://github.com/carols10cents/rustlings) — small exercises to get you used to reading and writing Rust code
  * [Rust Recipes ★8](https://github.com/kud1ing/rust-recipes) — short recipes how to do solve common problems in Rust
  * [stdx ★630](https://github.com/brson/stdx) — Learn these crates first as an extension to std
* Podcasts
  * [New Rustacean](http://www.newrustacean.com) — a podcast about learning Rust
  * [Rusty Radio](http://rustyrad.io) — covering the rust ecosystem
* [RustCamp 2015 Talks](http://confreaks.tv/events/rustcamp2015)
* [Rust Design Patterns](https://github.com/nrc/patterns)
* [Rust Guidelines](http://aturon.github.io/)
* [RustBooks ★142](https://github.com/sger/RustBooks) — list of RustBooks


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
---
<p align="center">
	This list is a copy of <a href="https://github.com/kud1ing/awesome-rust">https://github.com/kud1ing/awesome-rust</a> with ranks
</p>

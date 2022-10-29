# Awesome Cosmopolitan

<img align="left" src="images/cool-honeybadger-smaller.png">

This is a list of Cosmopolitan projects and resources. If you notice anything missing, please open a pull request or simply [make a suggestion](https://github.com/shmup/awesome-cosmopolitan/discussions/new?category=suggestion).

------

## Table of contents

- [Cosmopolitan](#cosmopolitan-)
  - [Programs](#programs)
  - [Ports](#ports)
  - [Blog Posts](#blog-posts)
- [Redbean](#redbean-)
  - [Projects](#projects)
  - [Blog Posts](#blog-posts-1)
- [Fullmoon](#fullmoon-)

------

## Cosmopolitan

> <img align="left" src="images/honeybadger_smaller.png"> _Cosmopolitan Libc makes C a build-once run-anywhere language, like Java, except it doesn't need an interpreter or virtual machine. Instead, it reconfigures stock GCC and Clang to output a POSIX-approved polyglot format that runs natively on Linux + Mac + Windows + FreeBSD + OpenBSD + NetBSD + BIOS with the best possible performance and the tiniest footprint imaginable._
>
> ![image operating systems](images/operatingsystems.png "operating systems")

- [Cosmopolitan](https://github.com/jart/cosmopolitan) - Build-once-run-anywhere for C
- [API Docs](https://justine.lol/cosmopolitan/documentation.html) - Thorough documentation for Cosmopolitan Libc
- [HN discussions](https://hn.algolia.com/?query=cosmoplitan+libc) - Algolia list of Cosmopolitan submissions

### Programs

- [actually portable awk](https://justine.lol/awk/) - The One True \[Portable\] [Awk](https://github.com/onetrueawk/awk)
- [apelife.com](https://justine.lol/apelife/index.html) - tui for conway's game of life with xterm mouse integration
- [blinkenlights](https://justine.lol/blinkenlights/) - Command line debugger that focuses on visualizing how software changes memory
- [bob](https://github.com/dinosaure/bob) - A peer-to-peer file-transfer tool in OCaml with Cosmopolitan
- [braille dump](https://justine.lol/braille/) - drop in replacement for hexdump -C that uses unicode braille characters to display hex code
- [memzoom.com](https://justine.lol/memzoom/index.html) - view/monitor the raw memory of processes/files in your UTF-8 terminal
- [nesemu1.com](https://justine.lol/nesemu1.html) - nes emulator in a terminal
- [printimage.com](https://justine.lol/printimage.html) - png/jpg/gif in terminals
- [printvideo.com](https://justine.lol/printvideo.html) - mpeg in terminals

### Projects
- [cosmo-include](https://github.com/fabriziobertocci/cosmo-include) - Set of very empty header files that can be used when building apps with Cosmopolitan
- [cosmosocks](https://github.com/bannsec/cosmosocks) - Socks server written in Cosmopolitan libc
- [microwindows](https://github.com/ghaerr/microwindows) - The Nano-X Window System ([demo](https://github.com/jart/cosmopolitan/issues/35#issuecomment-1098659862))

### Tilting at Windmills

Here are our most ambitious community projects, which would require perishing the greatest demons, but if it could be done, would yield some great rewards.

- [cosmogfx](https://github.com/jacereda/cosmogfx) - Build-once run-anywhere OpenGL application

### Ports

Note: Some ports are experimental. The most battle-tested code is in the [Cosmopolitan repo](https://github.com/jart/cosmopolitan). Ports are often a stepping stone for what we put in the monorepo.

- [blis](https://github.com/ahgamut/blis/tree/cosmopolitan) - Port of BLIS
- [cosmonim](https://github.com/Yardanico/cosmonim) - Simple example to show how cosmopolitan libc can be used with Nim
- [cpython311](https://github.com/ahgamut/cpython/tree/cosmo_py311) - Port of python 3.11 (see also [3.9](https://github.com/ahgamut/cpython/tree/cosmo_py39), [3.6](https://github.com/ahgamut/cpython/tree/cosmo_py36), and [2.7](https://github.com/ahgamut/cpython/tree/cosmo_py27))
- [esperanto](https://github.com/dinosaure/esperanto) - build-once run-anywhere OCaml programs
- [janet](https://github.com/ahgamut/janet/tree/cosmopolitan) - Port of Janet
- [lua](https://github.com/ahgamut/lua/tree/cosmopolitan) - Port of Lua
- [luajit](https://github.com/ahgamut/LuaJIT-cosmo) - Port of Lua JIT
- [make](https://github.com/ahgamut/gnu-make-cosmopolitan) - Port of GNU Make
- [nim](https://github.com/gnu-enjoyer/ActuallyPortableNim) - Turns Nim into a build once run anywhere language
- [perl](https://computoid.com/APPerl/) - Port of Perl
- [php73](https://github.com/ahgamut/php-src/tree/cosmo_php73) - Port of  PHP 7.3
- [ripgrep](https://github.com/ahgamut/ripgrep) - Port of ripgrep
- [rust ape example](https://github.com/ahgamut/rust-ape-example) - Rust APE Example
- [scalajs ape example](https://github.com/lolgab/cosmopolitan-scalajs-example) - Scala.js APE Example
- [sqlite](https://github.com/ahgamut/sqlite/tree/cosmopolitan) - Port of SQLite
- [tcl](https://github.com/ahgamut/tcl/tree/cosmopolitan) - Port of TCL
- [wasm3](https://github.com/wasm3/wasm3/blob/main/docs/Installation.md#cosmopolitan--actually-portable-executable) - APE of wasm3

### Blog Posts

- [Logging C Functions](https://justine.lol/ftrace/) - May 19th, 2022
- [Size Optimization Tricks](https://justine.lol/sizetricks/) - June 10th, 2022
- [Ape Loader](https://justine.lol/apeloader/) - June 11th, 2022
- [Porting OpenBSD pledge() to Linux](https://justine.lol/pledge/) - July 13th, 2022
- [Using Landlock to Sandbox GNU Make](https://justine.lol/make/) - Aug 7th, 2022
- [αcτµαlly pδrταblε εxεcµταblε](https://justine.lol/ape.html) - Aug 24th, 2020
- [Getting Started with Cosmopolitan Libc](https://jeskin.net/blog/getting-started-with-cosmopolitan-libc/) - Sep 4th, 2022

## Redbean

> <img align="left" src="images/redbean.png"> _redbean is an open source webserver in a zip executable that runs on six operating systems. The basic idea is if you want to build a web app that runs anywhere, then you download the redbean.com file, put your .html and .lua files inside it using the zip command, and then you've got a hermetic app you can deploy and share._

- [API Docs](https://redbean.dev/)
- [redbean-template](https://github.com/ProducerMatt/redbean-template) - Starting template to create your own redbean project
- [HN discussions](https://hn.algolia.com/?query=redbean) - Algolia list of redbean submissions

### Projects
- [action-static-redbean](https://github.com/TimonLukas/action-static-redbean) - GitHub action that creates a redbean
- [redbean-calcpad](https://github.com/shmup/redbean-calcpad) - Alternative take on a calculator
- [redbean-cardgames](https://github.com/shmup/redbean-cardgames) - Upcoming collection of cardgames playable in a browser
- [redbean-docker](https://github.com/kissgyorgy/redbean-docker) - The smallest possible web server in Docker!
- [redbean-jwt](https://github.com/w13b3/redbean-jwt) - JSON Web Token for redbean
- [rig](https://github.com/cdrubin/rig) - redbean interactive grapher
- [tiddly-bean](https://github.com/amreus/tiddly-bean) - Experiments with a redbean TiddlyWiki server
- [turfwar](https://github.com/shamblesides/turfwar) - IPv4 address turf war!

### Blog Posts

- [redbean 2.0](https://justine.lol/redbean2/) - June 16th, 2022
- [Unbelievably clever: Redbean 2 – a single-file web server that runs on six OSes](https://www.theregister.com/2022/06/20/redbean_2_a_singlefile_web/) - June 20th, 2022
- [Color Us Impressed: Redbean Runs A Web Server On Six Operating Systems](https://hackaday.com/2022/07/22/color-us-impressed-redbean-runs-a-web-server-on-six-operating-systems/) - July 22nd, 2022
- [Redbean on Fly](https://til.simonwillison.net/fly/redbean-on-fly) - July 24th 2022, Recipe for deploying a dockerized redbean to fly
- [Debugging with ZeroBrane Studio](https://news.ycombinator.com/item?id=32484206) - Aug 10th, 2022

## Fullmoon
> <img align="left" src="images/fullmoon.png"> _Fullmoon is a fast and minimalistic web framework based on Redbean -- a portable, single-file distributable web server._

- [Fullmoon](https://github.com/pkulchenko/fullmoon) - Fast and minimalistic web framework
- [HN discussions](https://hn.algolia.com/?query=fullmoon+framework) - Algolia list of Fullmoon submissions

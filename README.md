# Awesome Cosmopolitan

<img align="left" src="https://user-images.githubusercontent.com/118710/185776068-c1ddea8e-74ac-4214-9f2b-7a3902bf64d7.png">

This is a list of Cosmopolitan projects and resources. If you see anything missing, please open a pull request or simply [make a suggestion](https://github.com/shmup/awesome-cosmopolitan/discussions/new?category=suggestion).

------

## Table of contents

- [Cosmopolitan](#cosmopolitan-)
  - [Ports](#ports)
  - [Programs](#programs)
  - [Blog Posts](#blog-posts)
- [Redbean](#redbean-)
  - [Projects](#projects)
  - [Blog Posts](#blog-posts-1)
- [Fullmoon](#fullmoon-)

------

## Cosmopolitan ![image redbean](images/honeybadger_smaller.png)

> _Cosmopolitan Libc makes C a build-once run-anywhere language, like Java, except it doesn't need an interpreter or virtual machine. Instead, it reconfigures stock GCC and Clang to output a POSIX-approved polyglot format that runs natively on Linux + Mac + Windows + FreeBSD + OpenBSD + NetBSD + BIOS with the best possible performance and the tiniest footprint imaginable._
>
> ![image operating systems](images/operatingsystems.png "operating systems")

- [Cosmopolitan](https://github.com/jart/cosmopolitan) - Build-once-run-anywhere for C
- [API Docs](https://justine.lol/cosmopolitan/documentation.html) - Thorough documentation for Cosmopolitan Libc
- [HN discussions](https://hn.algolia.com/?query=cosmoplitan+libc) - Algolia list of Cosmopolitan submissions

### Ports

Note: Some ports are experimental. The most battle-tested code is in the [Cosmopolitan repo](https://github.com/jart/cosmopolitan). Ports are often a stepping stone for what we put in the monorepo.

- [blis](https://github.com/ahgamut/blis/tree/cosmopolitan) - Port of BLIS
- [cpython39](https://github.com/ahgamut/cpython/tree/cosmo_py39) - Port of python 3.9 (see also [3.6](https://github.com/ahgamut/cpython/tree/cosmo_py39) and [2.7](https://github.com/ahgamut/cpython/tree/cosmo_py39))
- [esperanto](https://github.com/dinosaure/esperanto) - build-once run-anywhere OCaml programs
- [janet](https://github.com/ahgamut/janet/tree/cosmopolitan) - Port of Janet
- [lua](https://github.com/ahgamut/lua/tree/cosmopolitan) - Port of Lua
- [luajit](https://github.com/ahgamut/LuaJIT-cosmo) - Port of Lua JIT
- [make](https://github.com/ahgamut/gnu-make-cosmopolitan) - Port of GNU Make
- [nim](https://github.com/gnu-enjoyer/ActuallyPortableNim) - Turns Nim into a build once run anywhere language
- [php73](https://github.com/ahgamut/php-src/tree/cosmo_php73) - Port of  PHP 7.3
- [rust example](https://github.com/ahgamut/rust-ape-example) - Rust APE Example
- [sqlite](https://github.com/ahgamut/sqlite/tree/cosmopolitan) - Port of SQLite
- [tcl](https://github.com/ahgamut/tcl/tree/cosmopolitan) - Port of TCL
- [wasm3](https://github.com/wasm3/wasm3/blob/main/docs/Installation.md#cosmopolitan--actually-portable-executable) - APE of wasm3

### Programs

- [blinkenlights](https://justine.lol/blinkenlights/) - Command line debugger that focuses on visualizing how software changes memory
- [braille dump](https://justine.lol/braille/) - drop in replacement for hexdump -C that uses unicode braille characters to display hex codes
- [printimage.com](https://justine.lol/printimage.html) - png/jpg/gif in terminals
- [printvideo.com](https://justine.lol/printvideo.html) - mpeg in terminals

### Blog Posts

- [αcτµαlly pδrταblε εxεcµταblε](https://justine.lol/ape.html) - Aug 24th, 2020
- [Logging C Functions](https://justine.lol/ftrace/) - May 19th, 2022
- [Size Optimization Tricks](https://justine.lol/sizetricks/) - June 10th, 2022
- [Ape Loader](https://justine.lol/apeloader/) - June 11th, 2022
- [Porting OpenBSD pledge() to Linux](https://justine.lol/pledge/) - July 13th, 2022
- [Using Landlock to Sandbox GNU Make](https://justine.lol/make/) - Aug 7th, 2022

## Redbean ![image redbean](images/redbean.png)

> _redbean is an open source webserver in a zip executable that runs on six operating systems. The basic idea is if you want to build a web app that runs anywhere, then you download the redbean.com file, put your .html and .lua files inside it using the zip command, and then you've got a hermetic app you can deploy and share._

- [API Docs](https://redbean.dev/)
- [redbean-template](https://github.com/ProducerMatt/redbean-template) - Starting template to create your own redbean project
- [HN discussions](https://hn.algolia.com/?query=redbean) - Algolia list of redbean submissions

### Projects
- [rig](https://github.com/cdrubin/rig) - redbean interactive grapher
- [tiddly-bean](https://github.com/amreus/tiddly-bean) - Experiments with a redbean TiddlyWiki server
- [redbean-docker](https://github.com/kissgyorgy/redbean-docker) - The smallest possible web server in Docker!
- [action-static-redbean](https://github.com/TimonLukas/action-static-redbean) - GitHub action that creates a redbean
- [redbean-cardgames](https://github.com/shmup/redbean-cardgames) - Upcoming collection of cardgames playable in a browser
- [redbean-calcpad](https://github.com/shmup/redbean-calcpad) - Alternative take on a calculator

### Blog Posts

- [redbean 2.0](https://justine.lol/redbean2/) - June 16th, 2022
- [Debugging with ZeroBrane Studio](https://news.ycombinator.com/item?id=32484206) - Aug 10th, 2022
- [Redbean on Fly](https://til.simonwillison.net/fly/redbean-on-fly) - Recipe for deploying a dockerized redbean to fly

## Fullmoon ![image fullmoon](images/fullmoon.png)

> _Fullmoon is a fast and minimalistic web framework based on Redbean -- a portable, single-file distributable web server._

- [Fullmoon](https://github.com/pkulchenko/fullmoon) - Fast and minimalistic web framework
- [HN discussions](https://hn.algolia.com/?query=fullmoon+framework) - Algolia list of Fullmoon submissions

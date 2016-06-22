# oh-my-gosh [![Travis-CI](https://api.travis-ci.org/ostera/oh-my-gosh.svg)](https://travis-ci.org/ostera/oh-my-gosh)
:scream: A collection of Portable Go utilities for your Shell

## Installation

```
go get github.com/ostera/oh-my-gosh
```

From source just run `make` and put the `gosh` executable somewhere handy.

## Usage

```
~ λ gosh

   Usage: gosh <command> [options]

   Commands:
     list                       lists available tools
     yes                        installs all available tools

   Options:
     -h, --help                 this help page
     -v, --version              print out version

```

#### Listing Tools

```
~ λ gosh list

+ github.com/siniec/winmake   -   A portable, barebones Go replacement for GNU's make
+ github.com/ostera/try       -   ♻️  A portable Go utility to retry commands with backoff
i github.com/ostera/watch     -   ⌚  A portable Go alternative to GNU's watch

```

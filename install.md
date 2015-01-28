---
layout: page
title: Install
permalink: /install/
---

## First Install Mono

**[Mono](http://www.mono-project.com/)**: Since Pash is written in C# and depends on the `.net` framework, it requires you to install [Mono](http://www.mono-project.com/).

- **Mac**: To install on a Mac, you can easily get Mono with [brew](http://brew.sh)

    `brew update && brew install mono`

- **Linux**: Checkout the **[Mono docs](http://www.mono-project.com/docs/getting-started/install/linux/)** for installing Mono on **Linux**.
- **Windows**: Checkout the **[Mono docs](http://www.mono-project.com/docs/getting-started/install/windows/)** for installing Mono on **Windows**.


# Pash Install

> Due to how often the project is undergoing changes, it's best to pull the latest from the source repository using [git](http://git-scm.com/)

- Get the code
  - **Prefer git**: `git clone https://github.com/Pash-Project/Pash.git`
  - Fall-back: download via curl `curl -L -o pash.zip http://github.com/pash-project/pash/zipball/master/` and unzip it.
- `cd Pash` (cd into the project)
- `xbuild` (this builds the project)

# Run it

`mono Source/PashConsole/bin/Debug/Pash.exe`

# Make it easy.

It's a bit more convenient to type `pash` at a prompt and jump into the `Pash Console` so setup little `alias` in your shell's profile (`.bash_profile`, `.zshrc`, other?) so you can run `pash` from anywhere and not have to type `mono ...Pash.exe` to spin up the shell each time.

EX:

`alias pash='mono ~/PATH_TO_PASH/Pash/Source/PashConsole/bin/Debug/Pash.exe'`

# What now?

Come checkout the [GitHub](https://github.com/Pash-Project/Pash) project, report bugs and help us out by sending in a pull requests...

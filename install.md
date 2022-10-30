---
title: Install
layout: default
---

# How to install SuperTux Advance?

## Latest Stable Build

You can download pre-built packages from here: https://kelvinshadewing.itch.io/supertux-advance

## Install from GitHub

To install SuperTux Advance, you need to download two things.

1. A Brux Runtime nightly build - get it from [here](http://kelvinshadewing.net/dl/brux-nightly.zip){:target="_blank"}.
2. SuperTux Advance source code - get it from [here](https://github.com/KelvinShadewing/supertux-advance/archive/refs/heads/main.zip){:target="_blank"}, or clone it, using `git`.

---

#### SuperTux Advance - Git download method (optional):

Cloning with `git` will allow you to get the latest STA updates by running `git pull`.

To clone the repository, make sure you have [Git](https://git-scm.com/){:target="_blank"} installed, and run `git clone https://github.com/KelvinShadewing/supertux-advance.git`.

---

After both resources are downloaded, make sure they are both extracted into different folders. To run STA, you need to open the `tux.brx` file from STA's source code, using `brux.exe` (or `brux` on Linux) from the Brux nightly download. You can associate `tux.brx` with these executables to make it open with a click.

## Tip!

You can also make a shortcut, which automatically starts `brux.exe`, by including `tux.brx`'s destination as a parameter. Use the following to create the shortcut, just by putting in the appropriate paths:

`{path-to-brux}\brux.exe" -f {path-to-sta}/tux.brx`

The path to `tux.brx` can be relative to the path of `brux.exe` (or `brux`).
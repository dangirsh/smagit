# smagit - Standalone Magit

## Overview

Git is great, but anyone who has used the command line interface has the scars to prove it. Many resort to [this](https://xkcd.com/1597/). If you feel this pain and are too cool for GUIs, keep reading.

[Emacs users](https://i.imgur.com/pznqq35.jpg) will often (smugly) mention a magical git interface within Emacs called [Magit](https://github.com/magit/magit). Magit is an interface to git that is intelligently-designed, keyboard-driven, and highly visual. [Here](https://www.emacswiki.org/emacs/Magit) is a good place to learn more.

The purpose of smagit is to provide the glory of Magit for non-Emacs users. This is done by tricking people into using Emacs, but just for Magit. If you are already an Emacs user, ignore this package and install Magit directly.

"I didn't actually understand git until I started using Magit." - Me

"... magit is a mode that I just basically live in. For any project that I’m working on, the magit buffer becomes the home buffer for that project, and I’m constantly looking at that buffer to see what work I’ve done, what work should be committed now." - [John Wiegley](https://github.com/jwiegley) ([source](http://sachachua.com/blog/2012/07/transcript-emacs-chat-john-wiegley/))

## Installation

1. Install [Emacs](http://emacs.sexy/) if you don't already have it.
2. Clone this repo: `git clone https://github.com/dangirsh/smagit`
3. Put a symlink to the top-level `smagit` script somewhere in your $PATH.
4. Execute `smagit` from within any Git repository.
5. Wait for packages to install (only happens the first time)
6. Upon success, you should see the "magit status" screen.

## Usage

From the "magit status" screen, get help by hitting the `?` key.

![smagit status](https://raw.githubusercontent.com/maio/smagit/master/images/smagit.png)

Useful links:

- [Magit documentation]()
- [Magit tutorial 1](https://www.masteringemacs.org/article/introduction-magit-emacs-mode-git)
- [Magit tutorial 2](https://github.com/jkitchin/magit-tutorial)
- [Magit cheat sheet](http://daemianmack.com/magit-cheatsheet.html)
- [Screencast](https://youtu.be/vQO7F2Q9DwA?t=2m44s)

## License

Copyright © 2016 Marian Schubert

MIT

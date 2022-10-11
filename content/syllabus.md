---
title: "Syllabus"
date: 2022-10-10T14:33:09-04:00
toc: true
---

## Unit 0 - Installation

- Setting up a bare-metal Linux machine
- Setting up QEMU/KVM (or just using boxes)
- Understanding how to actually install OS'es with an ISO

---

## Unit 1 - Filesystems

1. Understanding working directories (pwd, cd, ls)

2. Managing files and permissions (chmod, chgrp, touch, mkdir, rm, du, cp, mv)

3. Using nano

---

## Unit 2 - Essential Programs

1. Working with vim and neovim, the command-line text editor. (navigation, editing, some basic configuration)
2. Working with git (creating, pushing, branching), gitignores
3. Using your local package manager (and a meta-commentary on how they
   generally work).

### Projects

- Creating a class repository and uploading it to a Git Server.
- Creating a repository containing vim and dotfile configurations

---

## Unit 3 - Shell Scripting

1. local and environmental variables

- e.g. `env`, $PATH, $SHELL

2. Interpreters and shebangs

- sh, bash, zsh, fish

3. control statements (loops, conditionals, `test`, `case`)

4. Functions

5. UNIX pipelines (`| > <`, `awk`, `sed`, `grep`), interpolating (`$(command)`)

### Projects

- schoolwork manager
- dotfile post-installation script
- Generate a markdown file with title, name

## Unit 4 - Markup languages

- Using markdown and pandoc
- The basics of LaTeX

- Understanding how build tools are used and how to exploit them (make)

---

## Unit 5 - Networks and Regexes

1. CLI HTTP Clients (curl, wget) and HTTP status codes
2. Use of Regular Expressions

### Projects

- license picker (and downloader) with a simple CLI interface
- scrape AoPS to figure out the problem of the day (and figure out if it's a
  good enough level for someone)

---

## Unit 6 - Python Clients

1. Syntax, functions
2. The batteries-included stdlib (json, os, pathlib, argparse, re, filesystem API)
3. Using poetry and pip
4. Using external libraries (toml, requests, urllib3, numpy/scipy/matplotlib)
5. Scraping Libraries

### Projects (Difficulty Going Up!)

- Do a zipf's law word analysis on an (appropriate) site of your choosing
- Scrape basketball-reference.com to get a catalog of player salaries (and plot
  their distributions)
- Buff out whatever previous project
- **advanced** Use the GPT-3 API to generate summaries for news articles

---

## Unit 7

Unit 7 is a project-based unit, where you'll be making some useful web
application with some amount of variation. You'll do at least one, but it is
**possible** to do all of them in sequence.

This may be one of the most difficult and head-scratching experiences of your
life. It may take anywhere between 3 and 6 months.

### Unit 7A - Fullstack Web

1. HTML/CSS/JS (Will take a long time)
2. Flask Framework
3. Connecting to a database (sql or nosql) / Doing authentication
4. (**Optional**) Frontend frameworks (Vue or React)

After this unit, one should have a portfolio project and their own personal
website.

### Unit 7B - SysAdmin Web

1. SSH/Private Key authentication
2. Systemd services
3. Nginx: webserver and reverse proxy
4. Writing HTML
5. Buying domains/ Domain Records
6. PHP, CGI
7. Deploying apps of one's choice

### Unit 7C - The Web and Reproducibility (Advanced)

- Reproducible Philosophy: Docker, NixOS, Guix
- Writing web apps integrated with Nix Flakes
- Using an exotic language (e.g. lisp) for a project

---

## Unit 8: And Beyond

At this point, students should have gained the skills necessary to go off and do
exploration of their own. Depending on their interests, they may do one of the
following or something completely different:

- Venture into FREEBSD (Jails, different OS philosophies)
- Functional Programming (haskell, erlang, elixir)
- Compiled Languages (Go, Rust)
- BaaS (e.g. Firebase)
- Mobile Development

If you are interested in doing a collaborative project, just let me know.

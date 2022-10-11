---
title: "Schoolwork Manager"
date: 2022-10-10T22:44:18-04:00
unit: 4
---

Most Competitive Programmers have a "setup" of quick scripts that they use
to create, test, and submit solutions. With a couple of steps, it's adaptable to
your classwork too.

## Task

Create a single-file shell script with the following functionality:

1. Copy pre-designated templates over, which the user can specify
2. Rename files to assignment name (for example, a LaTeX project named `essay`
   should have an `essay.tex`, not a `template.tex`). Other files will probably
   have to change too. I'm a bit looser on this requirement, though.
3. A subcommand that lets a user compile whatever project they're in.
4. (Optional) make it POSIX-compliant, so it works on virtually every UNIX
   operating system.

## Resources

You can take inspiration from [MkTeX](https://github.com/junikimm717/Mktex).

This is a bit overkill, but there's always the [bash
bible](https://github.com/dylanaraps/pure-bash-bible).

Unless otherwise specified, this is all Nim code.

Some driving libraries & tools:
-------------------------------
 - [cligen](https://github.com/c-blake/cligen) - library to infer/generate
 command-line-interfaces / option / argument parsing; Also has some IO/system
 interface utility modules to have no dependencies
 - [adix](https://github.com/c-blake/adix) - A Data structures for Indexing lib
 with sketches
 - [nio](https://github.com/c-blake/nio) - Low Overhead Numerical/Native IO lib
 & tools organized around the idea of compact file extensions as schemas
 - [bu](https://github.com/c-blake/bu) - Over 50 (mostly cligen) CLI utilities
 covering space management, file typology & times, benchmarking, pipeline/data
 formatting/calculation, sysadmin, tty tools, Nim package release, parallel &
 queuing shell tools, various front ends for adix things, random sampling & MORE

Adding some more color to your life:
------------------------------------
 - [lc](https://github.com/c-blake/lc) - A post-modern, "multi-dimensional",
 colorful, configurable, abbreviating, extensible ls/file lister
 - [procs](https://github.com/c-blake/procs) - Colorful-like `lc`-Unix process &
 system query & formatting library & multi-command CLI
 - [hldiff](https://github.com/c-blake/hldiff) - A port of Python difflib to
 compute diffs and (re)highlight diff output intraline

Adding some math to your life:
------------------------------
 - [spfun](https://github.com/c-blake/spfun) - Special Functions Of Stats /
 Physics / Etc.
 - [fitl](https://github.com/c-blake/fitl) - Self-contained fit of linear models
 with regression diagnostics & various auto-regularization

Helping you handle graphs/words/documents:
------------------------------------------
 - [gralg](https://github.com/c-blake/gralg) - Classic algorithms on graphs (the
 linked structure, not plots)
 - [thes](https://github.com/c-blake/thes) - a library & CLI interface to Moby
 Thesaurus that saves the DB in a packed binary format
 - [suggest](https://github.com/c-blake/suggest) - A fast implementation of Mor
 & Fraenkel 1982's spell checking algo (co-opted/re-discovered by Wolfe Garbe)
 with a custom memory-mapped data file format/DB and some perf analysis
 - [ndup](https://github.com/c-blake/ndup) - Near-Duplicate File Detection Code

Miscellaneous:
--------------
 - [kslog](https://github.com/c-blake/kslog) - Lightweight Linux specific replacement for
 syslogd-ng in ~130 lines
 - [cron](https://github.com/c-blake/cron) - Very lightweight replacement for
 crond/tab in ~60 lines of Nim
 - [nimp](https://github.com/c-blake/nimp) - a Nim package manager I use (but
 doubt anyone else will) in ~320 self-contained lines
 - [ftab](https://github.com/c-blake/ftab) - Native File-Based Hash Table
 library like DBM; SQLite can be overkill/slow

An experiment:
--------------
 - [nimsearch](https://github.com/c-blake/nimsearch) - Try to explain some
 elementary ideas of search engine impl via successive diffs / patches

Some C packages:
----------------
 - [batch](https://github.com/c-blake/batch) - A Linux Kernel module to create a
 new `sys_batch` system call that runs packaged mini-programs with 1 kernel
 crossing
 - [bst](https://github.com/c-blake/bst) - Well Factored, Non-Recursive, General
 & Generic BSTs in ANSI C - unbalanced, AVL, red-black, Lk-weight & splay

# awesome-colored-output
Adding beauitful outputs to many commands to increase readability
for Terminal:

* [atuin](https://github.com/atuinsh/atuin) -  A shell history search tool that synchronizes across multiple machines. It enhances color output by highlighting search results, making it easier to debug and track command history.
* [bat](https://github.com/sharkdp/bat/) -  A cat clone with syntax highlighting and Git integration. It enhances readability of code by colorizing output, which aids in debugging.
* [bacon](https://github.com/Canop/bacon) - 
* [batpipe](https://github.com/eth-p/bat-extras/blob/master/doc/batpipe.md) -  A tool that provides extra functionality for bat, such as piping support. It also supports color output, making it easier to distinguish between different parts of the output.
* [bingrep](https://github.com/m4b/bingrep) -  Greps through binaries from various OSs and architectures, and colors them. This colorization helps in debugging by making it easier to identify patterns and anomalies.
* [Clink](https://github.com/chrisant996/clink) - Utilities for Command Prompt
* [Cppman](https://github.com/aitjcize/cppman) - C++ man pages in color
* [eza](https://github.com/eza-community/eza) -  A command line tool for easy access to common tasks. It uses color output to differentiate between different types of tasks.
* [fclones](https://github.com/pkolaczk/fclones) -  A tool to find duplicate files and directories. It uses color output to highlight duplicates, aiding in debugging and cleanup.
* [fd](https://github.com/sharkdp/fd) -  A simple, fast and user-friendly alternative to 'find'. It uses color output to enhance readability of search results.
* [gitdiff](https://github.com/dandavison/delta) -  A viewer for git and diff output. It uses color output to highlight differences, making it easier to debug and track changes.
* [gitui](https://github.com/extrawurst/gitui) -  A blazing fast terminal UI for git written in Rust. It uses color output to enhance the user interface, making it easier to navigate and debug.
* [grep](https://github.com/BurntSushi/ripgrep) -  A line-oriented search tool that recursively searches your current directory for a regex pattern. It uses color output to highlight matches, aiding in debugging.
* [grex](https://github.com/pemistahl/grex) -  A command-line tool and library for generating regular expressions from user-provided test cases. It uses color output to highlight matches and mismatches, aiding in debugging.
* [Manpager](https://github.com/Freed-Wu/manpager) -  A man pager with colored man pages, fast navigation, and more. It uses color output to enhance readability of man pages, making it easier to find and debug issues.
* [nanorc](https://github.com/scopatz/nanorc) -  Improved Nano Syntax Highlighting Files. It enhances color output in Nano, improving readability and aiding in debugging.
* [nu](https://www.nushell.sh/) -  A new type of shell that focuses on simplifying data manipulation tasks. It uses color output to enhance readability and ease of use.
* [procs](https://github.com/dalance/procs) -  A modern replacement for 'ps' written in Rust. It uses color output to enhance readability of process information, aiding in debugging.
* [rga](https://github.com/phiresky/ripgrep-all) -  A ripgrep wrapper that supports search in PDFs, E-Books, Office documents, zip, tar.gz, etc. It uses color output to highlight matches, aiding in debugging.
* [sd](https://github.com/chmln/sd) -  An intuitive find & replace CLI. It uses color output to highlight matches and replacements.
* [starship](https://starship.rs/) -  A minimal, blazing fast, and extremely customizable prompt for any shell. It uses color output to enhance the user interface, making it easier to navigate.
* [tealdeer](https://github.com/dbrgn/tealdeer) -  A very fast implementation of tldr in Rust. It uses color output to enhance readability of tldr pages, aiding in learning new commands.
* [less](https://github.com/wofr06/lesspipe) - less output 
* [curl](https://github.com/rs/curlie) - less output 

* [df replacement](https://github.com/muesli/duf)
* [top rpeplacement](https://github.com/ClementTsang/bottom)
* [hexyl](https://github.com/sharkdp/hexyl) -  A hex viewer for the modern era. It uses color output to enhance readability of hex data, aiding in debugging.
* [lnav](https://lnav.org/)



Tools: 
[coteditor](https://coteditor.com/)
[quick source code extension](https://github.com/sbarex/SourceCodeSyntaxHighlight)
[gdb](https://www.gdbgui.com/)
[WarpTerminal](https://www.warp.dev/)

Shell: 
* [zsh-help](https://github.com/Freed-Wu/zsh-help)
* [Zsh-Fast-Syntax-Hightling](https://github.com/zdharma/fast-syntax-highlighting)
* [mysqlcolorize](https://github.com/zpm-zsh/mysql-colorize/tree/master)
* [ls/eza](https://github.com/zpm-zsh/ls)
* [ble](https://github.com/akinomyoga/ble.sh) -  A Bash line editor to make your command line more powerful. It enhances color output to improve readability and ease of use.
* [ohmpyosh](https://ohmyposh.dev/) - powershell prompt
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) - output colorizer that utilizes grc

Commnad output
* [onefetch](https://github.com/o2sh/onefetch)
* [Python](https://github.com/Qix-/better-exceptions)
* [grc](https://github.com/garabik/grc) -  A generic colouriser that can be used to colourise different kinds of output. This helps in debugging by making it easier to distinguish between different parts of the output.
* [macchina](https://github.com/Macchina-CLI/macchina) - neofetch replacement
* Rust `export RUST_BACKTRACE=full`

```sh
export CLICOLOR=1
export LESS="$LESS -R"
export LESSOPEN='|~/.lessfilter %s'
export LESSCOLORIZER='bat'
export MANPAGER='manpager --style=plain | less --pattern=^\\S+'

# force C colored diagnostic output
export CFLAGS="${CFLAGS} -fdiagnostics-color=always"
# force C++ colored diagnostic output
export CXXFLAGS="${CXXFLAGS} -fdiagnostics-color=always"
export CCFLAGS="${CCFLAGS} -fdiagnostics-color=always"
# force C, C++, Cpp (pre-processor) colored diagnostic output
export CPPFLAGS="${CPPFLAGS} -fdiagnostics-color=always"

```




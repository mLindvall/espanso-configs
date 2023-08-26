# My Espanso Config

[Espanso](https://espanso.org/) is an open source, privacy-first, corss-platform text expander developed by [@federico-terzi](https://github.com/federico-terzi) and written in Rust. In short, it detects when you type a certain keyword, and replaces it on the fly with a pre-defined string or dynamic output.

This repository holds my personal configuration and matches (the actual text replacement snippets) for Espanso. Maybe it will be useful to someone else!

## Setup

- Install [Espanso](https://espanso.org/install/) if not already
- Run `espanso path` to determine where you're config should be stored. Within this folder, there should be a directory called `user/`, this is where you store all your custom scripts
- Fork this (or another) repo, and clone it to your system, then setup a symlink to the directory mentioned above. Running `espanso restart` will reload with your new config
- You can now edit the YAML files to meet your needs, and reload Espanso for changes to take effect

See Also: [Espanso: Getting Started](https://espanso.org/docs/get-started/)

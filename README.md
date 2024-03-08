# radvim

a blazingly-bad configuration for me learning neovim / experimenting with it! 

startup time is about 130ms (bad!)

## Installation

### Install External Dependencies

> **NOTE**
> [Backup](#FAQ) your previous configuration (if any exists)

External Requirements:
- Basic utils: `git`, `make`, `unzip`, C Compiler (`gcc`)
- [ripgrep](https://github.com/BurntSushi/ripgrep#installation)
- Language Setup:
  - If want to write Typescript, you need `npm`
  - If want to write Golang, you will need `go`
  - etc.

### Install radvim

```sh
git clone https://github.com/radstevee/radvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```

And then just run `nvim` and you're good to go!

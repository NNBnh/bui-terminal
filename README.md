<h1 align="center"><code>bui-terminal</code></h1>
<p align="center">Terminal colorscheme that <i>SuperB</i></p>
<p align="center"><img src="https://img.shields.io/github/license/NNBnh/bui-terminal?labelColor=073551&color=4EAA25&style=for-the-badge" alt="License: GPL-3.0"> <img src="https://img.shields.io/github/languages/top/NNBnh/b.sh?logo=gnu-bash&labelColor=073551&color=4EAA25&logoColor=FFFFFF&style=for-the-badge" alt="Shell: 100%"> <img src="https://img.shields.io/github/last-commit/NNBnh/bui-terminal?labelColor=073551&color=4EAA25&style=for-the-badge"></p>
<p align="center"><img src="https://img.shields.io/github/watchers/NNBnh/bui-terminal?labelColor=073551&color=4EAA25&style=flat-square"> <img src="https://img.shields.io/github/stars/NNBnh/bui-terminal?labelColor=073551&color=4EAA25&style=flat-square"> <img src="https://img.shields.io/github/forks/NNBnh/bui-terminal?labelColor=073551&color=4EAA25&style=flat-square"> <img src="https://img.shields.io/github/issues/NNBnh/bui-terminal?labelColor=073551&color=4EAA25&style=flat-square"></p>

## About
`bui-terminal` is a color scheme tool written in [`pure sh`](https://github.com/dylanaraps/pure-sh-bible) that change terminal colors on-the-fly independent of terminal emulator and uses [BUI environment variables](https://github.com/NNBnh/dots/wiki/bui).

## Contents
- [About](#about)
- [Contents](#contents)
- [Setup](#setup)
  - [Dependencies](#dependencies)
  - [Installation](#installation)
- [Usage](#usage)
- [Credit](#credit)

## Setup
### Dependencies
- `sh` to process

### Installation
#### Manually
- Option 1: using `curl`

```sh
curl https://raw.githubusercontent.com/NNBnh/bui-terminal/main/bui-terminal > ~/.local/bin/bui-terminal
chmod +x ~/.local/bin/bui-terminal
```

- Option 2: using `git`

```sh
git clone https://github.com/NNBnh/bui-terminal.git ~/.local/share/bui-terminal
ln -s ~/.local/share/bui-terminal/bui-terminal ~/.local/bin/bui-terminal
```

#### Package manager
`#TODO`

## Usage
Run `bui-terminal` in the terminal:

```sh
bui-terminal
```

## Credit
Special thanks to:
- [**Paleta**](https://github.com/dylanaraps/paleta) by [Dylan](https://github.com/dylanaraps), This project inspired me to make this tool.

> <h1 align="center">Made with ❤️ by <a href="https://github.com/NNBnh"><i>NNB</i></a></h1>
>
> <p align="center"><a href="https://www.buymeacoffee.com/nnbnh"><img src="https://img.shields.io/badge/buy_me_a_coffee%20-%23F7CA88.svg?logo=buy-me-a-coffee&logoColor=333333&style=for-the-badge" alt="Buy Me a Snack (Buy Me a Coffee)"></p>

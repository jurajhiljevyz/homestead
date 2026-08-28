# homestead

My shell and editor configs, managed with a tiny install script

## How to use

```bash
# configs are symlinked, edit here and it applies everywhere
```

## Installation

```bash
git clone <this repo> ~/.dotfiles
cd ~/.dotfiles
./install.sh
```

## What it does

- One-command setup: ./install.sh
- Bash prompt with git branch indicator
- Git aliases I actually use daily
- Sane vim defaults, no plugins required

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── development.md
│   └── usage.md
├── .bashrc
├── .editorconfig
├── .gitattributes
├── .gitignore
├── .vimrc
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── Makefile
└── install.sh
```

## Known issues

- none reported yet (surprisingly)

## License

MIT licensed, see LICENSE.

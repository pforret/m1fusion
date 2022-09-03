![bash_unit CI](https://github.com/pforret/m1fusion/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/m1fusion/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/m1fusion)
![GH stars](https://img.shields.io/github/stars/pforret/m1fusion)
![GH tag](https://img.shields.io/github/v/tag/pforret/m1fusion)
![GH License](https://img.shields.io/github/license/pforret/m1fusion)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://basher.gitparade.com/package/)

# m1fusion

Stable Diffusion for MacOS M1

## 🔥 Usage

```
Program: m1fusion 0.0.1 by peter@forret.com
Updated: 2022-09-03
Description: Stable Diffusion for MacOS M1
Usage: normal.sh [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] <action> <input?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] output more [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/normal]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: .tmp]
    <action>         : [parameter] action to perform: analyze/convert
    <input>          : [parameter] input file/text (optional)
```

## ⚡️ Examples

```bash
> m1fusion .
# start PhpStorm with current folder as project
```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/m1fusion

or with `git`

	$ git clone https://github.com/pforret/m1fusion.git
	$ cd m1fusion

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2022 Peter Forret

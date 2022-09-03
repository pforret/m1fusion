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
Program : m1fusion  by peter@forret.com
Version : v1.0.1 (Sep  3 22:13:48 2022)
Purpose : Stable Diffusion for MacOS M1
Usage   : m1fusion [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] [-s <style>] <action> <prompt?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] also show debug messages [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/m1fusion]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /tmp/m1fusion]
    -s|--style <?>   : [option] image style: photo/manga/comic
    <action>         : [choice] action to perform  [options: install,image,check,env,update]
    <prompt>         : [parameter] prompt (optional)
```

## ⚡️ Examples

```bash
> m1fusion install
# do the installation: MacOS, brew, python, git ...
> m1fusion image "new born kitten"
> m1fusion --style cinema image "new born kitten"
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

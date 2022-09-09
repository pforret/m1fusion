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
Version : v1.1.0 (Sep  9 22:12:14 2022)
Purpose : Stable Diffusion for MacOS M1
Usage   : m1fusion [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] [-S <style>] [-W <width>] [-H <height>] [-N <steps>] <action> <prompt?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] also show debug messages [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/m1fusion]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /tmp/m1fusion]
    -S|--style <?>   : [option] image style: cinema/photo/manga/comic/painting
    -W|--width <?>   : [option] output image width (max 512)  [default: 512]
    -H|--height <?>  : [option] output image height (max 512)  [default: 512]
    -N|--steps <?>   : [option] number of time steps  [default: 50]
    <action>         : [choice] action to perform  [options: install,uninstall,prompt,nsfw,check,env,update]
    <prompt>         : [parameter] prompt to use for image generation (optional)

### TIPS & EXAMPLES
* use m1fusion install to install Stable Diffusion
  m1fusion install
* use m1fusion uninstall to delete all Stable Diffusion files (7GB)
  m1fusion uninstall
* use m1fusion nsfw to disable Stable Diffusion NSFW filter
  m1fusion nsfw
* use m1fusion prompt to create an image from a prompt
  m1fusion prompt "a small kitten"
* use m1fusion check to check if this script is ready to execute and what values the options/flags are
  m1fusion check
* use m1fusion env to generate an example .env file
  m1fusion env > .env
* use m1fusion update to update to the latest version
  m1fusion update
* >>> bash script created with pforret/bashew
* >>> for bash development, also check IO:print pforret/setver and pforret/progressbar
```

## ⚡️ Examples

```bash
> m1fusion install
# do the installation: MacOS, brew, python, git ...

> m1fusion uninstall
# remove all Stable Diffusion files

> m1fusion nsfw
# disable the Rickroll NSFW filter

> m1fusion prompt "new born kitten"
> m1fusion --style cinema prompt "new born kitten"
# generate images
# get inspiration on e.g. https://prompthero.com/
```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/m1fusion

or with `git`

	$ git clone https://github.com/pforret/m1fusion.git
	$ cd m1fusion

## 📝 Acknowledgements

* StableDiffusion: [huggingface.co/spaces/stabilityai/stable-diffusion](https://huggingface.co/spaces/stabilityai/stable-diffusion) by [stability.ai](https://stability.ai/)
* Apple M1 instructions compiled by Pieter Levels [twitter.com/levelsio/status/1565731907664478209](https://twitter.com/levelsio/status/1565731907664478209)
* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2022 Peter Forret

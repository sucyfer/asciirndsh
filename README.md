![](https://github.com/sucyfer/asciirndsh/blob/master/screenshots/Screenshot_1.png)

# asciirndsh ![GitHub](https://img.shields.io/github/license/sucyfer/asciirndsh?color=%23df2626)   ![Maintenance](https://img.shields.io/maintenance/yes/2020)  [![Bash Shell](https://badges.frapsoft.com/bash/v1/bash.png?v=103)](https://github.com/ellerbrock/open-source-badges/)   [![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)



Simple bash script for generating random ascii art

## Installation

Clone repository, add execute permission to install scripts , install with install-update.sh and/or install-non-interactive.sh scripts,
add execute permission to installed script:

- `$ git clone https://github.com/sucyfer/asciirndsh.git`
- `$ cd asciirndsh/`
- `$ sudo chmod +x install-update.sh install-non-interactive.sh`
- `$ ./install-update.sh`
- `$ sudo chmod +x /usr/local/bin/asciirndsh`

Optional:
- `$ ./install-non-interactive.sh` (This adds `asciirndsh -rnd` to your `~/.bashrc` file which enables printing random ascii art on your
terminal every time you login or open a new terminal or terminal tab)

## Usage
All options and one-liners:

```
Usage:
asciirndsh [option] [arguments]

Options:
  -a, --add-category SOURCE                        add new category and new art in it
  -f, --file SOURCE                                add new .txt file as an new art
  -h, --help                                       show this help page
  -rmc, --remove-category                          remove category and all art under it
  --<category>                                     run the desired category of art without menu(ex : animals,computers,food, useradd...)  
```
## Tip

In code, you can edit names of menu entries and paths to their respective directories to your preference.

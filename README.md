![](https://github.com/sucyfer/asciirndsh/blob/master/screenshots/Screenshot_1.png)

# asciirndsh
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

You can edit names of menu entries and paths to their respective directories to your preference.

# nvidia-smi-gui
A Qt based GUI backend for monitering nvidia graphic devices through nvidia-smi.

## Dependencies:
* nvidia-smi
* python3
* PyQt5

## Installation
Install for the current user (into `~/.local`):

    $ pip install --user .

or, with [pipx](https://pipx.pypa.io/) into an isolated environment:

    $ pipx install .

`pip install --user` puts an `nvidia-smi-gui` command in `~/.local/bin`, and a
launcher and icon in `~/.local/share`, so the app shows up in your desktop's
application menu. pipx installs the command only, without the launcher.

## How to Use It

    $ nvidia-smi-gui

You can also run it straight from a source checkout without installing:

    $ ./nvidia-smi-gui.py

or

    $ python3 -m nvidia_smi_gui

## Screenshots
![Screenshot1](https://raw.github.com/imkzh/nvidia-smi-gui/master/screenshots/1.png "Status of the GPU installed on my computer")

![Screenshot2](https://raw.github.com/imkzh/nvidia-smi-gui/master/screenshots/2.png "Status of 4 GPUs installed on server")

## Credits
### Author

imkzh

### Icon for main window

`graphic-card.svg`: Icon made by [itim2101](https://www.flaticon.com/authors/itim2101) from www.flaticon.com 


### Icon for measurement indicators

`fan.svg`: Icon made by [Roundicons](https://www.flaticon.com/authors/roundicons) from www.flaticon.com

`gauge.svg`: Icon made by [Freepik](https://www.flaticon.com/authors/freepik) from www.flaticon.com

`wave.svg`: Icon made by [Twitter](https://www.flaticon.com/authors/twitter) from www.flaticon.com

`gear.svg`: Icon made by [Vectors Market](https://www.flaticon.com/authors/vectors-market) from www.flaticon.com

`ram.svg`: Icon made by [Freepik](https://www.flaticon.com/authors/freepik) from www.flaticon.com

`thermometer.svg`: Icon made by [Pixel Buddha](https://www.flaticon.com/authors/pixel-buddha) from www.flaticon.com


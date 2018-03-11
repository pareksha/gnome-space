# Gnome Space GRUB theme

## Disclaimer:
- This theme is a work of [Andrew Shevchuk](https://github.com/shvchk)
- I forked this repository just to make slight modifications so as to modify the theme as I like. I claim **not to be the owner of the project** and that all the content belongs to [Andrew Shevchuk](https://github.com/shvchk).
- Link to original repository is [here](https://github.com/shvchk/poly-light).

![Gnome Space GRUB theme](sample.jpg)

## Installation / update

1. **Automatic way:**
    - Download install script:  
    `wget -P /tmp https://github.com/sarthakthakur24/gnome-space/raw/master/install.sh`
    - Run it: `bash /tmp/install.sh`
2. **Manual way:**
    - Clone this repository
    ```
    git clone https://github.com/sarthakthakur24/gnome-space.git
    ```
    - Copy the theme to the Grub Themes directory
    ```
    sudo cp -r gnome-space /boot/grub/themes/
    ```
    - Open the grub configuration file stored in `etc/default/` with root permissions
    ```
    sudo gedit /etc/default/grub
    ```
    - Look for a line starting with `GRUB_THEME` and edit it to look like the one below:
    ```
    GRUB_THEME=/boot/grub/themes/gnome-space/theme.txt
    ```
    - Save the file and then exit the editor
    - Open a terminal and type `sudo update-grub` to update the grub with the new changes made in the grub configuration file.
    - You're all set to go. (:wink:)
    
## Contributors:
1. [Andrei Shevchuk](https://github.com/shvchk)
2. [格桑花给我的](https://github.com/Flowertome)
3. [Jonas Cosandey](https://github.com/velrest)
4. [Ole Martin Ruud](https://github.com/barskern)
5. [Ricardo Simões](https://github.com/Ricardo-Simoes)
6. [Sarthak Thakur](https://github.com/sarthakthakur24)

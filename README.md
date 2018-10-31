# debian_ansible

This is an ansible playbook I created for easy replication of my Debian desktop.

## Installed Tools
- Network Tools
- Python 2 / Pip
- Python 3 / Pip
- Pycharms
- gcc / make
- zip / 7zip / rar
- UFW
- git
- sudo

## Terminals
- ZSH
- Terminator
- Bash Completion

## Installed Applications
- Firefox
- Chrome
- Libre Office
- Evolution
- Shutter
- Gimp
- VLC
- KeepPass
- VMWare Workstation
- CherryTree Note
- Sublime Text
- byobu
- Dropbox

## Themes
- Axiom
- conky
- Flat-Remix (Light/Dark/Standard)
- la-capitaine
- Misc Wallpapers

# To Execute Playbook Locally
- Default Settings
> ansible-playbook site.yml
- Custom Settings
> ansible-playbook site.yml --extra-vars "user=joseph vm_key=00000-00000-00000-00000-00000"

**After playbook execution, you may need to run**
> ./.config/xfce4/XFCE-panel.sh
**If the panels don't update.**

## Example Screenshots 
![Example Desktop](https://github.com/jbarcia/debian_ansible/raw/master/Selection_060.png)

# 1. These are my persona notes
---
1. To move data from Ubuntu into windows
   * scp saboor@192.168.80.128:/home/saboor/report.txt "D:/Hacking"
   * This S-- is not allowed in alexxxle moves from Ubuntu into windows. saboor@192.168.80.128 is my vmware ip address

2. To move from Windows into Ubuntu
   * iscp -r "D:/Hacking/" saboor@192.168.80.128:/home/saboor/

### 2. To install nvim latest version
---
```bash
sudo add-apt-repository ppa:neovim-ppa/unstable
sudo apt update
```
### 3. Install Neovim
```
sudo apt install neovim
```
---

### 4. Ubuntu run terminal in the middle of screen

```bash
gsettings set org.gnome.mutter center-new-windows true
```

### 5. To remove it

```bash
gsettings set org.gnome.mutter center-new-windows false
```

* To find folders on Ubuntu
 ```bash
 bash bash find /usr/ -name fonts
 ```

### 6. Best aliases

* Here are my top aliases for windows 11. These are my favourite.

```
alias no="cd /c/Users/Username/AppData/Local/nvim"
alias load="source ~/.bashrc"
alias bashrc="vim ~/.bashrc"
alias dsk="cd ~/oneDrive/Desktop"
# source C:/Users/Username/miniconda3/Scripts/activate base
alias home="cd ~"
alias vim="nvim"
alias cc="clear"
alias remove="rm -rf"
alias go='cd'
# Open my notes from everywhere.
alias notes="nvim D:/notes.md"
# Sets standard user prompt
if [[ $EUID -ne 0 ]]; then
    PS1="\[\e[1;32m\]\u 🔐 \[\e[1;34m\]\w \[\e[0m\]"
# Sets root user prompt in bright red
else
    PS1="\[\e[1;31m\]\u 🔐 \[\e[1;34m\]\w \# \[\e[0m\]"
fi
eval "$(oh-my-posh init bash --config ~/oh_my_posh.json)"
```

### Run Flask

- run flask `flask --app app run`
- Or we can run live with debug:
  `export FLASK_DEBUG=1 && flask run`

[Google](https://www.google.com) -- This is google

#### Alter display tab.

`: 1, 10 l`
. This will show 1-10 lines like a split screen.

#### vim

. Select inside the {}, (), "", ''
`vim vi{ or vib`
. it does the same...


### Install ```bash Mariadb``` With Choco
``` choco install mariadb --pre```

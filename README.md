# basher
Makes your bash looks like kali 2020.3 ZSH

![](demo.gif)

## Installation
Just copy the whole file (`.bashrc`) from this repository, replace the one in your home directory with this one. Or you can copy and paste this customization from [this](https://github.com/azharizkita/basher/blob/main/.bashrc#L59-L79) selection, then just simply relaunch your terminal.

## Optional

### Make the .bashrc available for root user
CAUTION! This step will remove the default `/root/.bashrc file`, I strongly suggest you to backup the file before doing this.

(**Recommended**) Option A, replace the `/root/.bashrc`.
```bash
cd ~
sudo rm /root/.bashrc
sudo cp ~/.bashrc /root/.bashrc
```

Option B, make a symbolic link from your current home.
```bash
cd ~
sudo rm /root/.bashrc
sudo ln -s ~/.bashrc /root/.bashrc
```

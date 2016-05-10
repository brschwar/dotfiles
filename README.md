dotfiles
========

This repository contains the dotfiles to isntall when on a new mac, as well as a script to install and configure the mac with the following:

* List TBD

<br />
Step 1: Dotfiles
----------------

1. **Log into [GitHub](http://www.github.com)**


2. **[Generate SSH keys](https://help.github.com/articles/generating-an-ssh-key/)**

  Check to see if your keys exist. If not, then generate new SSH Keys:

  `ssh-keygen -t rsa -C "yourname@yourdomain.ext"`


3. **Add SSH key to GitHub**

  Copy the key then add it under GitHub Settings/SSH and GPG keys.

  `pbcopy < ~/.ssh/id_rsa.pub`


4. **Create Sites Folder**

  `mkdir ~/Sites && cd ~/Sites`

  and clone the dotfiles repo into Sites folder (you may be prompted to install command line tools).

  `git clone git@github.com:brschwar/dotfiles.git`


<br />
Step 2: Setup Script
--------------------

**Run script to setup Mac**

  - Script TBD


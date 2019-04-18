# Configuration Steps

To configure the terminal, we'll perform the following steps:

- rename allthe files: add the dot eg. `bash_profile => .bash_profile`
- move these files in:

    - `~/.config/git-completion.bash`
    - `~/.config/git-prompt.sh`

- move the bash_profile file to your home directory and name it `.bash_profile` (remember there's a dot at the front, now!)
  
    if you already have a .bash_profile file in your home directory, transfer the content from the downloaded bash_profile to your existing `.bash_profile` => [video](https://youtu.be/h00n9QLfbqU)

- In udacity-terminal-config thre are the original files - they are different from my current one. Useful as backup!

---

## First Time Git Configuration

Before you can start using Git, you need to configure it. Run each of the following lines on the command line to make sure everything is set up.

**sets up Git with your name**

`git config --global user.name "<Your-Full-Name>"`

**sets up Git with your email**

`git config --global user.email "<your-email-address>"`

**makes sure that Git output is colored**

`git config --global color.ui auto`

**displays the original state in a conflict**

`git config --global merge.conflictstyle diff3`

`git config --list`

**VSCode Setup**

`git config --global core.editor "code --wait"`
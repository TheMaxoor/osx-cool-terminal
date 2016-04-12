# OSX Cool Terminal
## WHAT IS THIS OMG !?
OSX Cool Terminal is basically a bash profile I wish I could find in the Interwebs, it's a template to have a nice CLI.

Here are the AWESOME features :
* AWESOME Colors
* AWESOME Random Emojis Each Line
* AWESOME Git completion (Thanks to official git files)
* AWESOME Git infos in prompt (Thanks to official git files)

Here is a screenshoterino :
![Badass Look](https://raw.github.com/TheMaxoor/readme-ressources/master/osx-cool-terminal/awesome-screenshot.jpg)

## How to install
It's easy my friend.

Just clone this repo in your home directory.

### Step 0 : Cloning
```
cd ~
git clone git@github.com:TheMaxoor/osx-cool-terminal.git
```

### Step 1 : Profile configuration
If the file .bash_profile is already created skip this command :
```
touch .bash_profile
```

Add these lines into it:
```
source ~/osx-cool-terminal/.git-completion.bash
source ~/osx-cool-terminal/.git-prompt.sh
source ~/osx-cool-terminal/.customization
```
The git files are required to handle git branch infos in the prompt

### Step 2 : CUSTOMIZE
You can directly go to the .customization file and edit it to match your preferences, you can easily change colors, emojis thanks to a lot of comments.

Have fun ! 😀

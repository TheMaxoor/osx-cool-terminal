# OSX Cool Terminal

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

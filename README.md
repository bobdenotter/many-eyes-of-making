# README

## Installation instructions:  

First we'll need to make a local copy of the Git repository that houses the notes. Then we'll install and set up Obsidian to use this folder.

### Clone the git repository

Go to the location on your machine where you'd like to have the notes. From there, run the following:  

```bash

git clone https://github.com/bobdenotter/many-eyes-of-making.git

```

### Install and set up Obsidian

First, if you don't have it installed yet, grab Obisidian from https://obsidian.md/

After opening the program, choose "Open Folder as Vault", and browse to the location where you've made the checkout of the Git repository:

![[Schermafbeelding 2021-11-01 om 17.09.27.png]]

Now you'll have a working copy of the notes, but it won't update automatically. To do that, we'll need to set up the "git" 

Go to settings, and click the 'Community Plugins' tab.

![[Schermafbeelding 2021-11-01 om 17.03.36.png]]

There, disable safe mode, and browse for extensions. In the search-box type `git` and the top suggestion will be "Obsidian Git". Install _**and**_ enable it. 

Finally, go to the "Obisidian Git" tab under community options, and enable "Pull updates on startup"

![[Schermafbeelding 2021-11-01 om 17.02.35.png]]


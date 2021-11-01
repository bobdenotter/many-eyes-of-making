# README

## Installation instructions:  

To set up a local copy of these notes, we'll need to make a clone of the Git repository that houses the entirety of the notes and images. Then we'll install and set up Obsidian to use this folder.

### Clone the git repository

Go to the location on your machine where you'd like to have the notes. From there, run the following:  

```bash

git clone https://github.com/bobdenotter/many-eyes-of-making.git

```

### Install and set up Obsidian

First, if you don't have it installed yet, grab Obisidian from https://obsidian.md/

After opening the program, choose "Open Folder as Vault", and browse to the location where you've made the checkout of the Git repository:

![](https://raw.githubusercontent.com/bobdenotter/many-eyes-of-making/main/Media/Installation/Schermafbeelding%202021-11-01%20om%2017.09.27.png)

Now you'll have a working copy of the notes, but it won't update automatically. To do that, we'll need to set up the "git" plugin for integration.

Go to settings, and click the 'Community Plugins' tab.

![](https://raw.githubusercontent.com/bobdenotter/many-eyes-of-making/main/Media/Installation/Schermafbeelding%202021-11-01%20om%2017.03.36.png)

There, disable safe mode, and browse for extensions. In the search-box type `git` and the top suggestion will be "Obsidian Git". Install _**and**_ enable it. 

Finally, go to the "Obisidian Git" tab under community options, and enable "Pull updates on startup"

![](https://github.com/bobdenotter/many-eyes-of-making/blob/main/Media/Installation/Screenshot%202021-11-01%20at%2018.30.38.png?raw=true)

You can do manual 'pull' operations through the command pallette: "Obsidian Git: Pull from remote repository".

---

### Pushing changes to Git

If you wish to push changes to Git, have Bob add your github username to the repository as a maintainer. 

Next, you'll need to configure the plugin to allow it to push straight to git from Obsidian: Go to Obsidian's 'Command Palette' (`CMD-P` on MacOs, probably `CTRL-P` on Windows) and select "Obisidian Git: Edit Remotes"

![](https://raw.githubusercontent.com/bobdenotter/many-eyes-of-making/main/Media/Installation/Schermafbeelding%202021-11-01%20om%2017.23.33.png)


Change the "Remote" to this URL: `git@github.com:bobdenotter/many-eyes-of-making.git`

Then, everytime you wish to push changes to git, you can use your favorite Git client, the command line, or the built-in "Obsidian Git: Create Backup" from Obsidian's Command Palette. 
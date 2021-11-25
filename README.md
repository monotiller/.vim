# vim
So, I wanted to have my own VIM configuration... and what better way to do that than to see what other people had been using? Using pluralsight's course titled "Smashing in to VIM" I was able to better understand how VIM works (I had an idea but was by no means and expert). Part of this tutorial talked more about how the plugin and configuration system in VIM works.

For some reason I hadn't had the idea to push my pre-existing configuration to source control but uhhh, here we are!

## Instructions
0. Inspect the configuration. If you're downloading this make sure you know what it's doing so you don't accidentally change things beyone recognition for your setup, you won't like that one bit, I promise you that!
1. Clone the repository. It doesn't matter where you put it but I like to put this in my home directory as that's where, by default, VIM looks for configuration files
2. As mentioned before, VIM looks for configuration files in `~` so you'll either need to change where VIM looks for these to where you cloned this repository, or, as I find far more easier, set up a symbolic link between the configuration files and where `.vimrc` is normally stored. This can be done by using the following command: `ln -nfs [path to folder]/.vimrc ~/.vimrc`. This will ensure that VIM will see the file even with your default settings. However it may also override any `.vimrc` that is present. This step may also be repeated for `.gvimrc` which is in control of theming VIM
3. Enjoy!

# config
Store configs, such as Awesome Window Manager config, IDE-configs etc.


# Awesome Window Manager
For running Awesome Window Manager on Ubuntu 16.04 as on Telia.

Put rc.lua at ~/.config/awesome/rc.lua

To change background, copy /usr/share/awesome/themes/default/theme.lua to .config/awesome/mytheme.lua and change theme.wallpaper = my-background.jpg

To have ssh-agent started on login and automatically and ssh-keys as needed:
put .xsession at ~/.xsession (or copy content into existing .xsession) this starts ssh-agent
also copy ssh-config to ~/.ssh/config.

To set vim as default editor:
 $ select-editor 
choose vim, vim.basic or vim.tiny

# IntelliJ config

Based on Intellij's Eclipse settings.
Import telia-intellij.settings from IntelliJ.

# jenv setup on mac:

add to shell .rc or .profile file.

export PATH="$HOME/.jenv/bin:$PATH"
eval "$(jenv init -)"

To get maven to pick up jenv version

$ jenv enable-plugin maven

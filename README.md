# Setup info


Install kitty and fish
```
brew install --cask kitty; brew install fish
```

Clone repo to ~/.config
```
git clone https://github.com/sitko-j/kitty-fish-config.git ~/.config/kitty/
```

You can install the fish plugin manager with.. (check out author repo here: jorgebucaran/fisher)
```
curl -sL https://raw.githubusercontent.com/jorgebucaran/fisher/main/functions/fisher.fish | source && fisher install jorgebucaran/fisher
```

After installing the plugin manager, you can install the 'tide' plugin to make the shell look prettier
```
fisher install IlanCosman/tide@v5
```

To configure tide run
```
tide configure
```

For an alternative colour scheme check out the commented out section of the config file, you can also use fisher to install other colour schemes

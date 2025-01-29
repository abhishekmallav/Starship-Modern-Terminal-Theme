# STARSHIP-Modern-Terminal-Theme

Terminal Customization with [Starship](https://starship.rs/)

1. clone the repository
   
   ```bash
   git clone https://github.com/abhishek-mallav/starship-modern-terminal.git
   ```

2. install starship
   
   ```bash
   curl -sS https://starship.rs/install.sh | sh
   ```

3. add the following line at the end of `.bashrc` file in `HOME` directory
   
   ```bash
   eval "$(starship init bash)"
   ```

4. paste the `starship.toml` file in `.config` directory

5. In order to display the icons in the `ls`command install the [LSD *(LSDeluxe)*](https://github.com/lsd-rs/lsd) package from github.

6. After the package is installed create bash aliases, edit the `.bash_aliases` file and add the following lines, if `.bash_aliases` file is not present in the `HOME` directory create the `.bash_aliases` file and paste the following in the file
   
   ```bash
   alias ls='lsd'
   alias l='lsd -l'
   alias la='lsd -a'
   alias lla='lsd -la'
   alias lt='lsd --tree'
   alias tree='lsd --tree'
   ```

----

Nerd Fonts are required for the graphics to display (any nerd font can work)

Nerd Fonts can be downloaded from [nerdfonts.com](https://www.nerdfonts.com/font-downloads)

If you want to further customize you can refer [starship](https://starship.rs/) documentation

![](https://github.com/abhishek-mallav/starship-modern-terminal/blob/main/starship-terminal-01.png)

![](https://github.com/abhishek-mallav/starship-modern-terminal/blob/main/starship-terminal-02.png)

![](https://github.com/abhishek-mallav/starship-modern-terminal/blob/main/starship-terminal-03.png)

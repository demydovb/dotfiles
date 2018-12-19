# My dotfiles
<h3> I am using zsh with oh-my-zsh as a main shell. I also have a lot of tools to make my working experience better. </h3>
 <hr>

You can follow these steps to install zsh with oh-my-zsh:

1. Install zsh: https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH
2. Install oh-my-zsh: http://ohmyz.sh/

<hr>
After that you can install very usefull plugin zsh-syntax-highlighting.
Follow these steps:

1. Clone this repository in oh-my-zsh's plugins directory:

        git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

2. Activate the plugin in ~/.zshrc:

        plugins=( [plugins...] zsh-syntax-highlighting)

3. Source ~/.zshrc to take changes into account:

        source ~/.zshrc

<hr>
Also, I use a plugin for auto-suggestions. To install it follow these steps:

1. Clone this repository into $ZSH_CUSTOM/plugins (by default ~/.oh-my-zsh/custom/plugins)

        git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

2. Add the plugin to the list of plugins for Oh My Zsh to load (inside ~/.zshrc):

        plugins=(zsh-autosuggestions)

3. Start a new terminal session.
<hr>

<h3>As a result of you will have a more powerful main shell and increase your command line productivity, like +100%</h3>
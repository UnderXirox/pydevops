# xDevOps/etc/zsh

Include:
1. zsh
2. oh-my-zsh

# How to install

Install zsh:

    sudo apt-get install zsh
    sudo yum install zsh

Install oh-my-zsh Use curl or wget(recommend):

    export ZSH="$HOME/.zsh.d/oh-my-zsh"; sh -c "$(curl -fsSL
    https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

    export ZSH="$HOME/.zsh.d/oh-my-zsh"; sh -c "$(wget
    https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh
    -O -)"

Install oh-my-zsh manual:

    git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.zsh.d/oh-my-zsh
    cp ~/.zshrc ~/.zshrc.orig
    chsh -s /bin/zsh

Configuration:

    echo "source ~/myCode/xDevOps/etc/zsh/zshrc" > ~/.zshrc

# How to use
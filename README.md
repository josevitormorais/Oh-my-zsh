# Oh-my-zsh
stylized terminal with dracula theme, if you don't like the theme, disregard this part.

required: installed git

# considerations
Why use this terminal with the proposed themes?

you will have much more agility and speed in the day to day work or study, if you use the command line a lot.

with details that will make all the difference for visualizing processes inside the terminal.

enough talk let's go to what matters!!! 

# first observation

I will consider that you use operating systems based on Unix (mac or linux), 
because in windowns it is very complicated to do the processes taught in this post,
unless you create a subsystem in linux within your windowns, otherwise this post it won't help you much.

# I want to show and share exactly how I set up my terminal, it helped me a lot and helps me a lot, so I need to share it with everyone.

## Installing Oh My Zsh

first, before getting down to earth, we need to install oh my zsh kk, as there are some peculiarities from one operating system to the other, I advise you to follow some recommendations in this guide: https://github.com/ohmyzsh/ohmyzsh


### so here we go, to install, Oh my zsh, run the command line below, it is necessary to have CURL installed.

sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

after the installation is done, all the settings will be made inside the ~ / .zshrc file and no longer ~ / .bash_profile or derivatives.

when you restart your terminal, you can already see some changes.

### now let's install the dracula theme, which for me is the most sensational theme, used in almost everything.

f you're on the Mac using the standard Terminal, you'll probably use: https://draculatheme.com/terminal/

If you are on Linux with a distribution that uses Gnome, you will use: https://github.com/dracula/gnome-terminal

# Theme Spaceship

I like this theme a lot, it gives you support to see versions of programs like, docker, node, etc.

let's clone then the reposotorio, with the command below

git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt"




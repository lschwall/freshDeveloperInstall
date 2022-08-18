# Fresh Install Program List (Mac)
###### v1.0.1

### Table of Contents

/ [Description](#description)   
/ [Base Program List](#base-program-list)  
/ [Optional Recommendations](#optional-recommendations)
/ [Front End Specific](#front-end)  
/ [Back End Specific](#back-end)

---
## Description
Base programs for basic development environment setup. Additionally, you can find front end and back end specific programs users find useful in development.

## Base Program List

###### Hyperlinks included in case you want to install via individual websites
 - [ ]  [HomeBrew.sh](https://brew.sh/)
 - [ ] [Git](https://git-scm.com/)
 - [ ] [vsCode](https://code.visualstudio.com/download)
 - [ ] [iterm2](https://iterm2.com/)
 - [ ] [NodeJs](https://nodejs.org/en/)
 - [ ] [NVM](https://npm.github.io/installation-setup-docs/installing/using-a-node-version-manager.html)
 - [ ] [eslint](https://eslint.org/) (optional)
 
> To install brew, copy this in your command terminal  
> ``/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"``  
> *make sure to check if there are any commands to run from the output*

>Copy and run these in your terminal after you installed brew  
> ``source ~/.bash_profile``  
> ``brew``

**Please close normal terminal and open iterm2 as you will be using this from now own**

>Once successfully verified brew installation, run these commands in your terminal  
>``brew install git`` => installs git  
>``brew install --cask visual-studio-code iterm2 node nvm`` => installs vscode,  iterm2, Nodejs, nvm  
>``brew doctor`` => this checks if there are any issues  

>*Optionally*, run this in iterm2 to install eslint  
>``npm install -g eslint eslint-config-airbnb eslint-plugin-import``
---
#### **Optional Extensions for vscode that are nice**
>##### All of these can be found in vscode's extension panel (it looks like 4 squares with 1 coming off)
> [Gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - lets you see who wrote the code  
> [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) - nicer icons  
> [Material Themes](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme) - nicer vscode ui/colors  
> [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - formats code  
>[ Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) - can open local host and run ur code  
>[ ES7+ React/Redux/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets) - autocomplete react code  
> [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) - autocomplete javascript code  
> [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - auto rename paired html tags  
> [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) - auto closes html tags  
> [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight) - highlights items marked with //TODO  
>[ Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare) - remote live code pairing (think google docs live editing)    
 
 >##### Alternatively you can just run this command in your terminal to install all of these
 >``code \``
 >``--install-extension eamodio.gitlens \``  
 >``--install-extension PKief.material-icon-theme \``  
 >``--install-extension Equinusocio.vsc-material-theme \``  
 >``--install-extension esbenp.prettier-vscode \``  
 >``--install-extension ritwickdey.LiveServer \``  
 >``--install-extension dsznajder.es7-react-js-snippets \``  
 >``--install-extension xabikos.JavaScriptSnippets \``   
 >``--install-extension formulahendry.auto-rename-tag \``   
 >``--install-extension wayou.vscode-todo-highlight \``   
 >``--install-extension MS-vsliveshare.vsliveshare``  

 ## Optional Recommendations
 - [DBeaver](https://dbeaver.io/) : Universal Database tool, see and edit your databases.
 - [jEnv](https://www.jenv.be/) : CLI to manage global and project specific JAVA versions
 - [bat](https://github.com/sharkdp/bat) : Like the cat command but with wings - Offers syntax highlighting and other features.
 - [fzf](https://github.com/junegunn/fzf) : interactive Unix filter for command-line that can be used with any list; files, command history, processes, hostnames, bookmarks, git commits, etc.
 - [exa](https://the.exa.website/) : A replacement for ls command with many features

## Front End

## Back End
---

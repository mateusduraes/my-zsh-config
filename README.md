## my-zsh-config

.zhrc file with my zsh framework config


### Installation

* Install zsh
  ```sh
    sudo apt-get install zsh
    zsh --version    
  ```
* Make zsh default shell
  ```zsh
    chsh -s $(which zsh)  
  ```
* Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
* Override .zshrc
* Relogin and it works


### My alias

```sh
alias gst="git status" 
alias gad="git add ."
alias gp="git push"
alias gc="git commit"
alias gcm="git checkout master"
alias gcd="git checkout develop"
alias ionicp="code . && ionic serve"
alias ngp="code . && ng serve"
```




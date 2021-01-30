# Настройки консоли для удобной работы с bash

## Отображение в консоли имени текущей ветки git:  

wget https://raw.githubusercontent.com/git/git/master/contrib/completion/git-prompt.sh  

~/.bashrc  

> . ~/git-prompt.sh  
export GIT_PS1_SHOWDIRTYSTATE=1  
export PS1='\u@\h \[\033[36m\]\w$(__git_ps1 "\[\033[32m\](%s)") \[\033[37m\]'  


## Автодополнение при работе с git:  

wget https://raw.githubusercontent.com/git/git/master/contrib/completion/git-completion.bash  

~/.bashrc  

>. ~/git-completion.bash  

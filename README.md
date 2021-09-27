# To install zsh with twoLine theme

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

curl -o ~/.oh-my-zsh/themes/twoLine.zsh-theme https://raw.githubusercontent.com/richardtbell/zsh-twoLine-theme/master/twoLine.zsh-theme 
sed -i -e 's/ZSH_THEME="robbyrussell"/ZSH_THEME="twoLine"/g' ~/.zshrc
source ~/.zshrc
```

https://medium.com/buildit/5-simple-tips-to-speed-up-your-development-environment-5a115290f5a1

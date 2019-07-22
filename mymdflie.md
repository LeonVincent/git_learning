### 出现zsh: command not found: xxx解决方法：
### 把 bash shell 中.bash_profile 全部环境变量加入zsh shell里就好

#### step1:
```
open .zshrc
```
#### step2:
找到 “# User configuration”
加入
```
source ~/.bash_profile
```

### step3:
```
source .zshrc
```

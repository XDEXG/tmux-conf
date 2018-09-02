# tmux-conf

## 1. install tmux


## 2. install tmux plugin manager: tpm
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

## 3. download .tmux.conf
```
cd
git clone https://github.com/xdexg/tmux-conf.git
ln -s ~/tmux-conf/.tmux.conf ~/.tmux.conf
# -n参数使得不覆盖已存在的本地配置文件。
cp -n ~/tmux-conf/.tmux.conf.local .
```

## 4. reload tmux environment
```
tmux source ~/.tmux.conf
```

## 5. installing plugins
在tmux中:
```
prefix + I
```

# cask-installer

## 使い方

1. インストールしたいアプリを検索

```
例） brew search google-chrome --cask
```

2. 「cask_formula.txt」にアプリの名前を列挙

```
例） 
docker
google-chrome
insomnia
insomnia-designer
iterm2
jetbrains-toolbox
middleclick
slack
tableplus
visual-studio-code
```

3. 実行権限の付与

```
sudo chmod +x cask_installer.sh
```


4. インストールの実行

```
sudo ./cask_installer.sh
```

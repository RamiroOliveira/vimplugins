# vimplugins
My vim plugins

## Instalation
```
cd ~/

git clone http://github.com/RamiroOliveira/vimplugins.git ~/.vimplugins

git submodule init

git submodule update
```

the last two git commands can be rolled in to one: `git submodule update --init.`

## Upgrading a plugin bundle
```
cd /media/vim/taglist

git pull origin master
```
## Upgrading all bundled plugins
`git submodule foreach 'case $name in YCM-Generator) git checkout stable ;; *) git checkout master ;; esac'`
`git submodule pull`

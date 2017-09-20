# vimplugins
My vim plugins

## Instalation
```
cd /media/vim

git clone http://github.com/RamiroOliveira/vimplugins.git /media/vim

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
`git submodule foreach git pull origin master` or if some plugin doesn't use master as the name of the branch
`git submodule foreach git pull`

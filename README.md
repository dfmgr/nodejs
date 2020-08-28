## nodejs  
  
A JavaScript runtime built on Chrome's V8 JavaScript engine  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/nodejs/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install nodejs yarn
```  

Fedora Based:

```shell
yum install nodejs yarn
```  

Arch Based:

```shell
pacman -S nodejs yarn npm
```  

MacOS:  

```shell
brew install nodejs yarn
```
  
```shell
mv -fv "$HOME/.config/nodejs" "$HOME/.config/nodejs.bak"
git clone https://github.com/dfmgr/nodejs "$HOME/.config/nodejs"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/nodejs" target="_blank" rel="noopener noreferrer">nodejs wiki</a>  |  
  <a href="https://nodejs.org" target="_blank" rel="noopener noreferrer">nodejs site</a>
</p>  

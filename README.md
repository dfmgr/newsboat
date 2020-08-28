## newsboat  
  
Newsboat is an RSS/Atom feed reader for the text console  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/newsboat/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install newsboat
```  

Fedora Based:

```shell
yum install newsboat
```  

Arch Based:

```shell
pacman -S newsboat
```  

MacOS:  

```shell
brew install newsboat
```
  
```shell
mv -fv "$HOME/.config/newsboat" "$HOME/.config/newsboat.bak"
git clone https://github.com/dfmgr/newsboat "$HOME/.config/newsboat"
newsboat -i  "$HOME/.config/newsboat/news.opml"
newsboat -x reload
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/newsboat" target="_blank" rel="noopener noreferrer">newsboat wiki</a>  |  
  <a href="https://newsboat.org" target="_blank" rel="noopener noreferrer">newsboat site</a>
</p>  

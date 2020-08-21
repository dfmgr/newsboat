## newsboat  
  
Newsboat is an RSS/Atom feed reader for the text console  
  
requires:    
```
apt install newsboat
```  
```
yum install newsboat
```  
```
pacman -S newsboat
```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/newsboat/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/newsboat" "$HOME/.config/newsboat.bak"
git clone https://github.com/dfmgr/newsboat "$HOME/.config/newsboat"
newsboat -i  "$HOME/.config/newsboat/news.opml"
newsboat -x reload
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/newsboat" target="_blank">newsboat wiki</a>  |  
  <a href="https://newsboat.org/" target="_blank">newsboat site</a>
</p>  

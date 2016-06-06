## dMenuRunExt
### Easy way start application with varies options
### Features
Start application with prefer options and selected file with function dMenuExlporer . 

### Requirements
Dynamic Menu Controller  has the following requirements:
- version 4.0 of bash or higher
- sed
- dmenu
- find
- awk
optional (edit script)
- tmux

### Usage
Clone with sumbodules 
git clone --recursive https://github.com/AdamKopanko/dMenuRunExt
changing permission allscripts in exet/ 
example:
cd ~/script/dMenuRunExt/ext/firebookmarks/
sudo chmod a+x firebookmarks

Bind in your favorite window mentager for dMenuRunEx.

Edit config:
example for mupdf  application
RUN_STRING['mupdf']='dMenuExplorer mupdf "'
Look in script for mor examples ...
### License

 This software is released under the terms of the
 GNU General Public License v2:
 [http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt](http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt)

### TODO

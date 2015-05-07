# urlviewer
A simple Spaceify example application

This is a simplest possible BigScreen-using Spaceify application.


*Installation*

Inside the spaceify VM do:

```bash
cd /home/spaceify
git clone https://github.com/ptesavol/urlviewer.git
cd urlviewer
sudo spm install /home/spaceify/urlviewer/volume
sudo service spaceify restart
```
*Usage*

Go to edge.spaceify.net with Firefox, and open a BigScreen. Then type an URL into the tile of UrlViewer and press the button. 
The page the URL points to should now be displayed in an iframe on the big screen. 

*Development*

You can simply make a copy of this application to create your own. However, remember to modify at least the spaceify.manifest
file to avoid naming conflicts with the original application. The application logic is implemented in files:

```bash
urlviewer.js
www/tile.html
www/screen.html
```
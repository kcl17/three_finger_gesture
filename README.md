# gestures-fix-ubuntu

First you need to reinstall your gnome-shell

```

sudo apt-get install --reinstall ubuntu-gnome-desktop

```

Then install gnome extension manager
```
sudo apt install gnome-shell-extension-manager
```
Now open the extension manager <br>
<div align="center">
<img src="https://github.com/Nikhil690/gestures-fix-ubuntu/assets/118874572/934757c1-8d37-4b2f-8490-857177a5e7bd" width="670">
</div>


Now search for X11 Gestures exntension and install it 
<div align="center">
<img src="https://github.com/Nikhil690/gestures-fix-ubuntu/assets/118874572/44a98407-4dd2-463e-9e3a-b236d89e533d" width="670">
</div>

lastly run these to enable it
```
sudo add-apt-repository ppa:touchegg/stable
sudo apt update
sudo apt install touchegg
```

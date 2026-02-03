## GPU Screen Recorder packages for Void Linux
Use with [xbps-src](https://github.com/void-linux/void-packages)

Copy over the packages
```
cp -r srcpkgs/ path/to/void-packages
```
Build a pacakge
```
./xbps-src pkg <package_name>
```
Install a package
```
sudo xbps-install --repository hostdir/binpkgs <package_name>
```
Alternatively with xtools
```
sudo xi <package_name>
```

# home-bin

Add home-bin to your PATH variable so that utils are accessible to bash

```sh
cd ~/repos && git clone https://github.com/nikolasovilj/home-bin.git &&\
echo export PATH=${PATH}:/home/$USER/repos/home-bin >> .bashrc
```
## TODO:

- [ ] ```cds``` - like ```cd``` but can change directories that come from stdout
- [ ] ```hasExif``` - if no arguments are passed, searches current directory for pictures and videos and prints full pathname of those containing EXIF metadata
- [ ] ```printAll``` - prints all files from the current directory or specified one, can print files of a certain extension and/or name (regex)
- [ ] ```author/license info insertion``` into existing scripts that don't have it

# home-bin

Add home-bin to your PATH variable so that utils are accessible to bash

```sh
cd ~ && git clone https://github.com/nikolasovilj/home-bin.git &&\
 user=`whoami` && echo export PATH=\$PATH:/home/$user/home-bin >> .bashrc
```
## TODO:

- [ ] ```cds``` - like ```cd``` but can change directories that come from stdout

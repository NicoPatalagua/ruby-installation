# Ruby installation
 
 # Installation on Mac OSX 📜

To install Ruby we will use a package manager called [rvm] (https://rvm.io/)
which will allow you to have several versions of Ruby installed on your machine.

## Process 💻

To install `rvm` and Ruby run the following commands:

```
sudo apt-get install libgdbm-dev libncurses5-dev automake libtool bison libffi-dev
gpg --keyserver hkp: //keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
curl -sSL https://get.rvm.io | bash -s stable
source ~ / .rvm / scripts / rvm
rvm install 2.3.3
rvm use 2.3.3 --default
ruby -v
```

⚠**NOTE:** _When executing the last command you should see the version of Ruby you just installed._

---
## By 📌
[NicoPatalagua](https://www.instagram.com/nicopatalagua/) 😎

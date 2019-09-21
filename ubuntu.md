
# Ubuntu installation

The first step to install Ruby on Ubuntu is to install some dependencies with the following commands:

``
sudo apt-get update
sudo apt-get install git-core curl zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev python-software-properties libffi-dev
``

The way we recommend installing Ruby is with [rvm] (https://rvm.io/), a version manager that will allow you to have several versions of Ruby installed on your machine. To do so, execute the following commands:

``
sudo apt-get install libgdbm-dev libncurses5-dev automake libtool bison libffi-dev
gpg --keyserver hkp: //keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
curl -sSL https://get.rvm.io | bash -s stable
source ~ / .rvm / scripts / rvm
rvm install 2.3.3
rvm use 2.3.3 --default
ruby -v
``

When executing the last command you should see the version of Ruby you just installed.


```sh
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
\curl -sSL -k https://get.rvm.io | bash -s stable
source /home/vagrant/.rvm/scripts/rvm
rvm use 2.1 --install --binary --fuzzy
cd /vagrant/
bundle install
```
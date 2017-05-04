
```sh
sudo apt-add-repository -y ppa:rael-gc/rvm
sudo apt-get update
sudo apt-get install rvm


exit

rvm use 2.1 --install --binary --fuzzy --create
cd /vagrant/www/
bundle install
```
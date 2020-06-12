<h1 align="center" size="20px">Laravel + Vue</h1>

## Homestead environment
# Install VirtualBox
Link: https://www.virtualbox.org/wiki/Downloads

# Vagrant (https://www.vagrantup.com/downloads.html)

# Installing
```bash
# Installing The Homestead Vagrant Box
vagrant box add laravel/homestead

# Installing Homestead
git clone https://github.com/laravel/homestead.git ~/Homestead
cd ~/Homestead
git checkout release

// Mac / Linux...
bash init.sh

// Windows...
init.bat

# Configuring Homestead
Homestead.yaml

# Hostname Resolution

# Vagrant start
vagrant up
```

## Laravel Installing
```bash
# First, download the Laravel installer using Composer
composer global require laravel/installer

# Laravel installation
laravel new lar-vue
cd lar-vue
```

# Install Asdf




# Can't connect to MySql 

 Manjaro: Can't connect to MySQL server through socket '/run/mysqld/mysqld.sock' (2 "No such file or directory") 




# Issue on ASDF Ruby 
PKG_CONFIG_PATH=/usr/lib/openssl-1.0/pkgconfig RUBY_EXTRA_CONFIGURE_OPTIONS="--with-openssl-dir=/usr/lib/openssl-1.0" asdf install ruby 2.3.3



# Installing Node on Asdf

## Run this to update gpg keys
bash ~/.asdf/plugins/nodejs/bin/import-release-team-keyring

## Continue Installation
asdf install


## Setting Up Shell
### Switching to fish

#### Install fish

```
yay -S fish
```


#### To set fish as default shell

Determine fish path

```which fish```

Set default shell to fish

```chsh -s /usr/local/bin/fish```


#### Install OH MY FISH (OMF)

```curl -L https://get.oh-my.fish | fish```


##### Set omf plugins & fonts_

```
sets the theme 
omf install budspencer

set -g theme_powerline_fonts no
set -g theme_nerd_fonts yes

set -U fish_key_bindings fish_vi_key_bindings

``` 

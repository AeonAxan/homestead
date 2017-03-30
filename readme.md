<p align="center"><img src="https://laravel.com/assets/img/components/logo-homestead.svg"></p>

## Introduction

This is a fork of original Laravel homestead that allows you to specify the PHP version per site.

## Installation

Get the box and add it to vagrant
```
vagrant box add azaan/homestead file:///home/azaan/package.box
```

Clone the repo and init
```
git clone https://github.com/aeonaxan/homestead
cd homestead
./init.sh
```

This will create a `conf` folder with the homestead config. Edit the file `conf/Homestead.yaml` to add your sites, etc.

Start the box from the cloned homestead folder
```
vagrant up
```

You can use the values `5.5` `5.6` and `7.0` for the php versions in the `Homestead.yaml` file





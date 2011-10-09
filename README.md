Cakper Symfony Bootstrap
========================

It's my private project for easy setting up new Symfony2 projects.

This package basis on 2.0.1 version of this great framework and inclueds:

* .htaccess fix for non-RewriteBase hosts
* umask configuration for non-ACL filesystems


Installation
------------

### Add your user to www-data group

In example in Debianoids it would be:

    sudo usermod -a -G www-data username


### Install Node.js, npm and less

    wget http://nodejs.org/dist/node-v0.4.12.tar.gz
    tar xvfz node-v0.4.12.tar.gz
    cd node-v0.4.12
    ./configure
    make
    sudo make install
    cd ../
    rm -rf node-v0.4.12
    sudo curl http://npmjs.org/install.sh | sh
    cd /usr/local/lib/node_modules
    sudo npm install less
    
    
    

Development Box
===============

A development environment created with 
[vagrant](http://vagrantup.com/ "Vagrant Homepage").

Environment
-----------

We use [rvm](http://beginrescueend.com/ "Ruby Version Manager") to
control the installed gems. A `.rvmrc` file controls the gemset
used.

Make sure to install vagrant with the following command

    > gem install vagrant

Vagrant
-------

Make sure to install the correct base box.

    > vagrant box add lucid32 http://files.vagrantup.com/lucid32.box

Vagrant can now be stared with the `up` command

    > vagrant up
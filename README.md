vagrant-pgsql9
==============

vagrant-pgsql9 allows you to run Postgresql 9.1 on VirtualBox.

Install
=======


1. Install VirtualBox<br/>
https://www.virtualbox.org/wiki/Downloads

1. Install Vagrant

    $ gem install vagrant

1. Add a box

    $ vagrant box add precise32 http://files.vagrantup.com/precise32.box

1. Clone this repository


That's it!


Play with Postgresql
====================

### Open terminal and move directory

    $ cd [path/to/repo/]

### Launch VirtualBox via Vagrant

    $ vargrant up

### Connect to postgresql

    $ psql -h 127.0.0.1 -p 15432 -u postgres

### Stop VurtualBox via Vagrant

    $ vagrant halt




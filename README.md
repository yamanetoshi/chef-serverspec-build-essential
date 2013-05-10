# build-essential 

## prerequisiet
Please prepare the Vagrant virtual resource in the following ways:

    $ vagrant box add test http://files.vagrantup.com/precise32.box
    $ mkdir hoge
    $ cd hoge
    $ vagrant init

Please git clone the repository in the directory _hoge_.

And, there is a need to introduce a gem package for the execution of rspec and chef.

## install the build-essential package
You can install in the following way.

    $ cd chef-repo
    $ knife solo cook 192.168.33.10

## execution of serverspec
You can check by running the _rake spec_.

## conclusion
It can be used to verify installation of build-essential package of Debian.


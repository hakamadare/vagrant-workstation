# Centos 6 Workstation (Vagrant)

## The first time

1. Install [Vagrant](http://vagrantup.com).
2. `vagrant up`
3. `vagrant vbguest --do rebuild`
4. `vagrant reload`

## When you've finished working

1. `vagrant suspend` or `vagrant halt`

## To resume

1. `vagrant resume` or `vagrant up`

## To reset to original state

1. `vagrant destroy`
2. `vagrant up`
3. `vagrant vbguest --do rebuild`
4. `vagrant reload`

# vagrant-percona-playground

You've seen it in the title, this is a playground.

## Why?

It's basically using Jays Vagrantscripts (http://github.com/jayjanssen/vagrant-percona), and putting them in different directories, so I can be worryfree and do 'vagrant up' and 'vagrant destroy' whenever I want (making symlinks is hard for me, it also makes me forget doing 'vagrant destroy' before I change the symlink, causing machines to 

## How

simple:

```
$ git clone --recursive https://github.com/grypyrg/vagrant-percona-playground
$ cd vagrant-percona-playbook
$ cd single_node
$ vagrant up --provider=aws	# virtualbox is default
```


when done

```
$ vagrant destroy
```


## How to configure aws with vagrant?

See https://github.com/jayjanssen/vagrant-percona#aws-setup

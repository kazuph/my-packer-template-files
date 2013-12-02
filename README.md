my-packer-template-files
========================

my packer template files

## install packer for mac

```
brew tap homebrew/binary
brew install packer
```

## make box image

```
$ cd my-packer-template-files/centos6.5
$ packer build -only=virtualbox template.json
```

## vagrant box add

```
vagrant box add centos6.5 packer_virtualbox_virtualbox.box
```


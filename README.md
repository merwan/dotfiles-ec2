dotfiles.git
============
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure your `vim` development environment as follows:

```sh
cd $HOME
git clone https://github.com/merwan/dotfiles-ec2.git ~/dotfiles
ln -sb dotfiles/.vimrc .
mv .vim .vim~
ln -s dotfiles/.vim .
```

See also http://github.com/merwan/setup to install prerequisite programs.

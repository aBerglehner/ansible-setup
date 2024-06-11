# ansible-setup

# To test run docker and if changes build docker before

## docker build -t nvim-computer .

## docker run --rm -it nvim-computer bash

# Otherwise make sure ansible is installed

### apt update && apt install -y software-properties-common && apt-add-repository -y ppa:ansible/ansible && apt update && apt install -y curl git ansible build-essential

## ansible-playbook local.yml

## ansible-playbook -t dotfiles local.yml -> -t for flag (dotfies)

# little work afterwards

## chmod + x and run after_ansible_install.sh in ~/.dotfiles folder

## for fd you need to execute this line to use it as fd

## ln -s $(which fdfind) ~/.local/bin/fd

## also make sure that $HOME/.local/bin is in your $PATH

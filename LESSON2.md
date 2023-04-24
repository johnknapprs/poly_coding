# Lesson 2

## Set Git Username & Email

```shell
git config --global user.name "John Knapp"
git config --global user.email "knappj2@gmail.com"
```

## Installing Ruby with RBenv

Install Packages in Ubuntu Linux

```shell
sudo apt install git curl libssl-dev libreadline-dev zlib1g-dev autoconf bison build-essential libyaml-dev libreadline-dev libncurses5-dev libffi-dev libgdbm-dev
```

Install RBenv

```shell
curl -fsSL https://github.com/rbenv/rbenv-installer/raw/HEAD/bin/rbenv-installer | bash
```

Set RBenv in Shell Environment (zshell)

```shell
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(rbenv init -)"' >> ~/.zshrc
source ~/.zshrc
```

List Ruby Versions to Install

```shell
rbenv install -l
```

Install Ruby's Latest Version

```shell
rbenv install 2.7.6

# Set Global Version
rbenv global 2.7.6
```

Basic Data Types

<https://www.theodinproject.com/lessons/ruby-basic-data-types>
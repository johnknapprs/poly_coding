# Lesson 2

## Set Git Username & Email

```shell
git config --global user.name "John Knapp"
git config --global user.email "knappj2@gmail.com"
```

## Installing Ruby with RBenv

Install Packages in Ubuntu Linux

```shell
sudo apt install zsh git curl libssl-dev libreadline-dev zlib1g-dev autoconf bison build-essential libyaml-dev libreadline-dev libncurses5-dev libffi-dev libgdbm-dev

# Set zshell to default
chsh -s $(which zsh)
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
rbenv install 3.2.0

# Check Ruby is Installed
ruby -v

# Set Global Version
rbenv global 3.2.0
```

Basic Data Types

<https://www.theodinproject.com/lessons/ruby-basic-data-types>

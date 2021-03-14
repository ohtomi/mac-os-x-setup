# mac-os-x-setup

This playbook provisions Mac OS X using Ansible 2.x.

## Usage

```zsh
$ sudo softwareupdate --install --recommended
$ sudo xcodebuild -license
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ git clone https://github.com/ohtomi/mac-os-x-setup ~/src/github.com/ohtomi/mac-os-x-setup
$ cd ~/src/github.com/ohtomi/mac-os-x-setup
$ brew update
$ brew install ansible
$ ansible-playbook -vv <playbook.yml>
```

## License

[MIT](https://ohtomi.mit-license.org)

## Author

[Kenichi Ohtomi](https://github.com/ohtomi)

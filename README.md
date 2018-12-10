# mac-os-x-setup

This playbook provisions Mac OS X using Ansible 2.x.

## Usage

```bash
$ sudo softwareupdate --install --recommended
$ sudo xcodebuild -license
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ git clone https://github.com/ohtomi/mac-os-x-setup ~/src/github.com/ohtomi/mac-os-x-setup
$ cd ~/src/github.com/ohtomi/mac-os-x-setup
$ brew update
$ brew install ansible
$ ansible-playbook site.yml -vv --ask-become-pass
# or
$ ansible-playbook site.yml -vv --extra-vars="@private.yml"
```

## License

[MIT](https://ohtomi.mit-license.org)

## Author

[Kenichi Ohtomi](https://github.com/ohtomi)

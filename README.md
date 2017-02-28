# mac-os-x-setup

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
```

## Contributing

1. Fork it!
1. Create your feature branch: `git checkout -b my-new-feature`
1. Commit your changes: `git commit -am 'Add some feature'`
1. Push to the branch: `git push origin my-new-feature`
1. Submit a pull request :D

## License

MIT

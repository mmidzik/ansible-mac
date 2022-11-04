Ansible setup for mac

1. `xcode-select --install`
2. `easy_install --user pip`
3. `pip install --user ansible`
4. `export PATH="~/.local/bin:$PATH"`
5. Check `ansible localhost -m ping`
6. Sign into Mac App Store (mas login doesn't work on new OS: see https://github.com/mas-cli/mas/issues/164)
7. Then `ansible-playbook playbook.yml`


Homebrew for M1
```
cd /opt
sudo mkdir homebrew
sudo chown $(whoami):admin homebrew
curl -L https://github.com/Homebrew/brew/tarball/master | tar xz --strip 1 -C homebrew
```
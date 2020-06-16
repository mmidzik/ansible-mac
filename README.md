--------
1. `xcode-select --install`
2. `easy_install --user pip`
3. `pip install --user ansible`
4. `https://raw.githubusercontent.com/ansible/ansible/devel/examples/ansible.cfg -o /etc/ansible/ansible.cfg`
5. Check `ansible localhost -m ping`
6. Sign into Mac App Store (mas login doesn't work on new OS: see https://github.com/mas-cli/mas/issues/164)
7. Then `./playbook.yml`
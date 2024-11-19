# コマンド

## セットアップ

```sh
brew install ansible
ansible-galaxy install newrelic.newrelic_install
ansible-galaxy collection install ansible.windows ansible.utils
```

## playbookの実行

```sh
ansible-playbook -i inventory.yml playbook.yml
```

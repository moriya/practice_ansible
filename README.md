## 概要

ansibleの練習で作成した ansibleのplaybookです。

## 前提条件

- 管理対象ノード
Ubuntu 22.04 LTS on Vagrant

- コントロールノード
Ubuntu on WSL2

## 実行手順

### リポジトリのclone

git clone https://github.com/moriya/practice_ansible.git

### 設定ファイルの変更
- inventory/hosts に 管理対象ノードのIPアドレスを設定する
- private_key にssh秘密鍵を設定する

### ansibleの実行

ansible-playbook playbook.yml

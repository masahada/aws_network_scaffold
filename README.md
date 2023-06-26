# aws network scaffold

デモ環境やテスト環境を作成するにあたって、定型化したVPC周辺を
Ansibleを使用して自動で作成する。

イメージ


■Ansibleインストール
AWS Cloudshellを起動し、リポジトリ上のinstall.txt の内容をシェルに貼り付けて実行。

■YAMLファイルの貼り付け
・シェル上で"vi main.yml"を実行
・リポジトリ上のmain.ymlの内容をviに貼り付ける
・":wq"を実行

■Ansibleの実行
・シェル上で"ansible-playbook main.yml"を実行

# aws network scaffold

デモ環境やテスト環境を作成するにあたって、定型化したVPC周辺を
Ansibleを使用して自動で作成する。

イメージ
image_aws_network.png
https://github.com/masahada/aws_network_scaffold/blob/2968c1e96bbc9a03e414b93b2f5d2d0d80e351ef/image_aws_network.png

■Ansibleインストール
AWS Cloudshellを起動し、リポジトリ上のinstall.txt の内容をシェルに貼り付けて実行。

■YAMLファイルの貼り付け
・シェル上で"vi main.yml"を実行
・リポジトリ上のmain.ymlの内容をviに貼り付ける
・":wq"を実行

■Ansibleの実行
・シェル上で"ansible-playbook main.yml"を実行

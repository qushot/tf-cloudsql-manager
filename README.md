# tf-cloudsql-manager
指定したCloud SQLインスタンスをCloud Schedulerで起動・停止するやつ


## Terraformのメモ。。。
- `.terraform.lock.hcl`: よくある外部パッケージのバージョンを固定するやつ。`terraform init`するとこいつを見る。
- `terraform init -upgrade`: `.terraform.lock.hcl`のプラグインバージョンを上げてくれるらしい。
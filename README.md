# 作成手順

```
$ cd fvm_vscode_template
$ fvm use stable
$ fvm flutter create . --project-name fvm_vscode_template
$ fvm install // 都度実施
$ fvm releases // 都度確認
```

# renovate 導入手順

1. https://github.com/apps/renovate で設定を行う
1. renovate/configure というpull requestが作られる
1. https://docs.renovatebot.com/configuration-options/ を参考にrenovate.jsonを編集する
# my-weekly-dep-update

毎週金曜日に実施している、[Tomachi (book000)](https://github.com/book000) が運用する一部のプロジェクトにおける依存パッケージアップデートの手助けをするスクリプトを置いたリポジトリです。

## Features

ほぼ GitHub Actions で動作します。

### Request dependencies update at every week

依存パッケージアップデート用の Issue をこのリポジトリで作成し、そこのコメントに各プロジェクトのワークフローリングを貼って各プロジェクトのアップデートを楽にします。

- GitHub Actions
- 日時: 毎週金曜日 午前9時(JST)
- [weekly-update.yml](https://github.com/book000/my-weekly-dep-update/blob/main/.github/workflows/weekly-update.yml)
- [実行結果](https://github.com/book000/my-weekly-dep-update/actions/workflows/weekly-update.yml)

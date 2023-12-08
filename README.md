# dart_lint

Flutter プロジェクト用の Dart の リントルール。
自前のリントルールを設定する。
方針としては、`` に全てのリントルールを追加し、必要ないルールは`analysis_options`で無効にする。
all_lint_rules.yaml の内容は下記で確認することができる。
https://dart.dev/tools/linter-rules/all

# メモ

- flutter のバージョン管理
  - fvm を使用してる
  - vscode にバージョンを指定してる

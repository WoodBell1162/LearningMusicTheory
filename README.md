# サウンドクエスト（ローカルミラー）

概要
- このフォルダは https://soundquest.jp/quest/ の目次に合わせてローカルに作成したフォルダ構成を保持します。
- 各記事フォルダには空の `memo.md` を配置しています（メモやURLを書き込む用途）。
- フォルダ番号は2桁ゼロ埋め（例: `I 0` → `I 00`, `P 1` → `P 01`）に整形済みです。

ルート
- パス: このリポジトリのルートに配置されています。

簡単な操作例（PowerShell）
```powershell
# フォルダツリー表示（再帰）
Get-ChildItem -Recurse -Directory | Sort-Object FullName

# 個別の memo.md にURLを書き込む例
Set-Content -Path "E:/Document/音楽勉強/サウンドクエスト/序論/I 00 凡例/memo.md" -Value "https://soundquest.jp/quest/..."
```

次のステップ（提案）
- 各 `memo.md` に対応する記事のURLを自動追記します（希望する場合、実行します）。
- 作成したフォルダ一覧をファイルまたは画面に出力して最終確認します。

ご希望を教えてください。
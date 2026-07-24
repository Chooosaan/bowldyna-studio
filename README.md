# Bowldyna Studio GitHub Pages

App Store Connect用の公開ページ一式です。

## 含まれるページ

- `/`：アプリ紹介ページ
- `/support/`：サポートページ
- `/privacy/`：プライバシーポリシー

## 公開前に必ず行うこと

全ファイルにある次の文字列を、公開用の問い合わせメールへ置換してください。

```text
SUPPORT_EMAIL_HERE
```

Linux例：

```bash
find . -type f -name '*.html' -print0 | xargs -0 sed -i 's/SUPPORT_EMAIL_HERE/your-email@example.com/g'
```

## GitHub Pages公開手順

1. GitHubで `bowldyna-studio` などのPublicリポジトリを作成
2. ZIPの中身をリポジトリ直下へアップロード
3. GitHubの `Settings` → `Pages`
4. `Build and deployment` のSourceを `Deploy from a branch`
5. Branchを `main`、Folderを `/(root)` に設定して保存
6. 数分後に公開URLを確認

想定URL：

```text
https://<GitHubユーザー名>.github.io/bowldyna-studio/
https://<GitHubユーザー名>.github.io/bowldyna-studio/support/
https://<GitHubユーザー名>.github.io/bowldyna-studio/privacy/
```

## App Store Connectへの入力

- サポートURL：`https://<GitHubユーザー名>.github.io/bowldyna-studio/support/`
- プライバシーポリシーURL：`https://<GitHubユーザー名>.github.io/bowldyna-studio/privacy/`
- マーケティングURL（任意）：`https://<GitHubユーザー名>.github.io/bowldyna-studio/`
# bowldyna-studio

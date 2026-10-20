# Git練習リポジトリ

Gitの操作を練習する際に作成したテキストファイルと、その変更履歴を確認するための小さなリポジトリです。実行可能なアプリケーションではありません。

## 現在のファイル

| ファイル | 内容 |
| --- | --- |
| `practice2.txt` | 練習用ファイル |
| `practice3.txt` | 練習用ファイル |
| `practice9.txt` | 練習用ファイル |
| `practice11.txt` | 練習用ファイル |
| `practice13.txt` | 練習用ファイル |

現時点のスナップショットには空のファイルも含まれています。依存パッケージやビルド手順はありません。

## 変更履歴の確認

```bash
git clone https://github.com/scribefire/git-practice-80.git
cd git-practice-80
git log --oneline --all --decorate
git branch --all
```

個別ファイルの変更は、`git show <commit>` または `git log -- <file>` で確認できます。

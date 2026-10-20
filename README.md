# Gitの練習用リポジトリ

Gitの練習で使った `practice*.txt` と、その変更履歴を置いています。

## 履歴を見る

```bash
git clone https://github.com/scribefire/git-practice-80.git
cd git-practice-80
git log --oneline --all --decorate
git branch --all
```

個別ファイルの変更は `git log -- practice9.txt` や `git show <commit>` で確認できます。

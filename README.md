# GitHub CLI の学習

GitHubのパブリックなリポジトリを作成し、クローンする

```terminal
gh repo create github-cli-example --public --clone
✓ Created repository mendelssohnbach/github-cli-example on GitHub
  https://github.com/mendelssohnbach/github-cli-example

$ git remote -v
origin	git@github.com:mendelssohnbach/github-cli-example.git (fetch)
origin	git@github.com:mendelssohnbach/github-cli-example.git (push)
```

VSCode でコミット後に **ブランチの発行** をクリックすると リポジトリにプッシュされる

issue を作成する  
issue 番号も自動で発行される

```terminal
gh issue create -t "
sample issue" -b "これはサンプルのイシューです" -a "@me"

Creating issue in mendelssohnbach/github-cli-example

https://github.com/mendelssohnbach/github-cli-example/issues/1
```

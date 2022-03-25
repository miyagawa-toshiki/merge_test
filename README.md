# merge_test
<h1>カレーライス</h1>
<li>branch : https://backlog.com/ja/git-tutorial/stepup/07/</li>
<p>git branch issue1 : issue1という名前のブランチを作成
<p>git branch : ブランチ名表示
<p>git checkout issue1 : issue1のブランチに切り替える</p>
<p>git checkout -b issue1:-bで作成とチェックアウトを一緒に行える</p>
# M       README.md
# Switched to branch 'issue1'
<p>add : 変更をインデックスに登録する
addしてからコミット
<p>git commit -m "addの説明を追加" : commitには理由をかける
#[issue1 28a9a81] addの説明を追加
# 1 file changed, 2 insertions(+)
# create mode 100644 file.txt

gitのブランチはパラレルワールド。addするとgitの追加する準備ができます。コミットする


1, rm -rf .git


2, ステージング：vscodeのプラス
3, add pushをまとめたのがコミット：vscodeのチェック
4, git push : githubに反映
  
  
<ローカルにリモートリボジトリを繋げる>
4, git init
5, git remote add origin https://github.com/PRTIMES/hackathon2022-spring-flask_noob.git
6, git branch -M main
7, git push -u origin main

git fetch
  
fetchとmergeが合わさったのpull
  
git ignore
  
git rm -rf --cached .venv

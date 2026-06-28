This repository is only for general practice .
steps:
mkdir practice
cd practice
git init --->[This creates .git in practice folder]
touch file.txt
echo "write something">file.txt
git add file.txt
git status
touch f1.txt
echo "write something">f1.txt
touch readme.md
echo "write something">readme.md
git add .
git status
git commit -m "Updated Snapshot"


git remote add orgin url  [orgin--github nickname][setting address to push]
git remote - v
git push -u orgin master[first push]
git push




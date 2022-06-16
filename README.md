第一次建立github需要以下動作
git init
git status
git add .
git config --global user.email "samsungduos7001@gmail.com"
git config --global user.name "smj700f"
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/smj700f/test.git
git push -u origin main

之後要上傳只需要以下動作就好
git status
git add .
git commit -m "first commit"
git push -u origin main

補充:
git add -A  提交所有變化
git add -u  提交被修改(modified)和被刪除(deleted)文件，不包括新文件(new)
git add .  提交新文件(new)和被修改(modified)文件，不包括被刪除(deleted)文件

# my-cs-61b
Update and store some code of CS-61B while self-learning!

# 1. 启动 SSH 代理（如果未启动）
eval "$(ssh-agent -s)"

# 2. 查看已加载的密钥
ssh-add -l

ssh-add "C:/ssh-keys/.ssh/id_ed25519"  # 你的私钥保存路径

ssh -T git@github.com

# 查看当前远程地址
git remote -v

git add lab1/*
git commit -m "done with Collatz"
git push origin master
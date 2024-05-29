# studyNotes-app-git
git 命令的学习笔记
## 配置 git
git config --global user.name "<your_name>" #配置姓名
git config --global user.email "<your_email>" #配置邮箱
## 创建 git 仓库
git init
## 克隆现有仓库
git clone <url>
## 检查当前状态
git status
## 添加文件到暂存区
git add <filename> #“git add .” 指令可能会更常用些
## 提交更改
git commit -m "<描述信息>"
## 新建新分支
git branch new-branch #注意: 必须提交一次文件才能使用 #此项存疑
## 查看远程仓库
git remote -v #此项存疑
## 推送到远程仓库
git push origin main #此项未验证
## 从远程仓库拉取
git pull origin main ##此项未验证
## 查看变更
git diff

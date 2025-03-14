#确认安装
git --version

#初始化
git config --global user.name "xxx"
git config --global user.email "xxx"
git init #最好在需要上传的目录下初始化

#基础提交操作
git status #查状态
git add xx.xx/.xx/.
git commit -m "日志备注“

#查询日志
git log
git log --oneline
git diff 日志码 -- 想查询的文件 #查询添加以外的修改
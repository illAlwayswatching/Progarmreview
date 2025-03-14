#确认安装
git --version

#初始化
git config --global user.name "xxx"
git config --global user.email "xxx"
git init                              #最好在需要上传的目录下初始化

#基础提交操作
git status #查状态
git add xx.xx/.xx/.
git commit -m "日志备注“

#查询日志
git log
git log --oneline
git diff 要对比的版本 -- 想查询的文件     #查询添加以外的修改

#还原日志
git checkout 要还原的版本 -- 想还原的档案 #该变动也需要提交
git reset -- hard 要退回的版本          #退回后之后的版本消失

#档案的删除和添加 也需要提交哦

#建立.gitignore 以保证无关文件不上传
好了接下来就是github
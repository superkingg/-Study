1、git上传项目的相关代码
cd 进入项目文件
git init     当前目录生成本地git管理
git add .    将项目所有文件添加到仓库
git commit -m "描述内容"         提交内容
git remote add origin http//:仓库地址      关联到github上
git push -u origin master         代码上传到github仓库
tips:如果出现远程库与本地库不一致，使用命令行git pull --rebase origin master

2、git返回上一目录 'cd ..'

# git 使用教程

## git查看配置信息

```nginx
$ git config --list
```

## 创建仓库命令

```nginx
git init #初始化仓库
git clone #拷贝一份远程仓库
```

## 提交与修改

```nginx
git add #添加文件到暂存区
git status #查看仓库当前的状态，显示有变更的文件。
git diff #比较文件的不同，即暂存区和工作区的差异。
git commit #提交暂存区到本地仓库。
git reset #回退版本。
git rm #将文件从暂存区和工作区中删除。
git mv #移动或重命名工作区文件。
```

## 提交日志

```nginx
git log #查看历史提交记录
git blame <file> #以列表形式查看指定文件的历史修改记录
```

## 远程操作

```nginx
git remote #远程仓库操作
# git remote -v 查看远程仓库链接
# git remote add origin https://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@github.com/DaiXiaoT/diary.git
git fetch #从远程获取代码库
git pull #下载远程代码并合并
git push #上传远程代码并合并
```


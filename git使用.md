# git使用

## 基本流程

* 克隆 Git 资源作为工作目录。
* 在克隆的资源上添加或修改文件。 
* 如果其他人修改了，你可以更新资源。
* 在提交前查看修改。
* 提交修改。
* 在修改完成后，如果发现错误，可以撤回提交并再次修改并提交。

![基本流程](https://www.runoob.com/wp-content/uploads/2015/02/git-process.png)

## 基本操作

### 建立仓库

```
git init newrepo
```

### 推送

```
git add .
git commit -m "操作说明"
git push -u origin main
```

### 下载

```
git fetch -all
git reset --hard origin/main
git pull
```

### 参考资料
[git教程]:https://www.runoob.com/git/git-tutorial.html

* [git教程]
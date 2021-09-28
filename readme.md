> 歌德曾说：读一本好书，就是在和高尚的人谈话。同理可得：读源码，也算是和作者的一种学习交流的方式。

## 代码结构

### git subtree

使用 git subtree 在多个 git 项目间双向同步子项目，但这里只是单向……

```shell
# 引入子仓库
git remote add -f <仓库别名> <仓库地址>
# 添加子仓库
git subtree add --prefix=<prefix> <repository> <ref>
```

## koa-compose

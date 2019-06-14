# blog_Project
博客项目

git clone 项目 之后

- 缺少的文件夹

```
 1.   .deploy_git   //文件夹
 2.   node_modules  //文件夹
 3.   db.json       //文件
 4.   public        //文件夹

```

操作流程


1. npm install

2. 在项目根目录下新建 db.json，文件内容

```json
{"meta":{"version":1,"warehouse":"2.2.0"},"models":{"Asset":[],"Cache":[],"Category":[],"Data":[],"Page":[],"Post":[],"PostAsset":[],"PostCategory":[],"PostTag":[],"Tag":[]}}
 
```
3 public 是 执行 `hexo g` 的上线的项目，再次执行 即可

4 .deploy_git 如果没有 与 是否 `npm install`  有关 ，或者 `npm install hexo-deployer-git --save ` ,在执行 `hexo d` ,应该就会出来


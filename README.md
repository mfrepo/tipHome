# 关于TIP
* TIP 即Thought In Practice, 知行合一之意
* 该仓库将开源TIP所有学习方法、工具、思想和项目实践，与社区一同探讨学习提升之道

## 项目架构
* 项目采用github page部署运行 
* 运行方式： 博客网站 
* 运行地址： https://mfrepo.github.io/tipHome/

## 参与共创, 成为TIP作者
* checkout代码到本地
```shell
git clone https://github.com/mfrepo/tipHome 
```
* 创建代码分支
```shell
Git branch <branch-name>
git checkout <branch-name>
```
* 进入docs/_posts目录，新增文件 
```text
文件格式遵守 "yyyy-mm-dd-标题.md"
```
* 提交分支请提交PR, Repo Admin会定期Review然后merge并发布到网站
```shell
git commit -m "请准确描述提交内容, 并squash多次commit"
git push
```

## 技术栈
* ruby/gem  
* bundle/jekyll
* github page
* nginx

## 本地编译运行
```shell
cd docs
bundle install
bundle exec jekyll serve
```

## 联系
mentorfinder@163.com

## 加入微信交流群
![](img/contact.jpeg )


## Feature Logs

### 项目初始化
```text
1. folk template from: https://jekyllthemes.io/github-pages-themes
2. change folder to docs
3. follow 本地编译运行步骤运行博客项目
```

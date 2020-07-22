## 安装hexo
npm install -g hexo

## 初始化hexo
hexo init
npm install hexo --save

## 生成静态页面至hexo\public\目录
hexo g

## 本地启动服务  http://localhost:4000/
hexo server

## 放到自己的GitHub上去
npm install hexo-deployer-git --save
hexo g
hexo d

## 博客 https://eiqli.github.io/

## 新修改的 修改完执行下面代码
hexo clean
hexo g
hexo d

## 更换主题 进入项目

git clone 主题地址 themes/cover
拷贝完成后，你会发现你的项目下的themes下多了一个cover文件夹
修改_config.yml文件中的一处来应用新的主题

# Extensions
## Plugins: http://hexo.io/plugins/
## Themes: http://hexo.io/themes/
theme: cover

## 然后重启就可以看到了
hexo server

## 各种主题地址
https://github.com/hexojs/hexo/wiki/Themes
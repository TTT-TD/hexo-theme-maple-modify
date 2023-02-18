# Hexo-theme-maple-modify
修改自[xbmlz/hexo-theme-maple](https://github.com/xbmlz/hexo-theme-maple)

- 修改了markdown`'`'`的显示方式
- 修复了nav部分在文章页面下header-title显示category的问题
- 加入了[hexo-admonition](https://github.com/lxl80/hexo-admonition)样式，需先执行`npm install hexo-admonition --save`命令安装

## 安装方法
```bash
cd /opt/hexo #进入博客目录
git clone git@github.com:TTT-TD/hexo-theme-maple-modify.git themes/
vim _config.yml #编辑博客的配置文件
```
```diff
- theme: some-theme
+ theme: maple
```

```bash
cd themes/maple #进入主题目录
mv _config.yml.example _config.yml #重命名配置文件
vim _config.yml #修改配置文件
```

```yaml
# Header
nav:
  Home: /
  Archives: /archives
  Categories: /category
  Tags: /tag

# favicon
# favicon: /favicon.png
favicon: /images/logo.svg
# logo
logo: /images/logo.svg

# links
links:
  #Github: https://github.com/xbmlz
  Telegram: https://t.me/impiuifu
  RSS: /atom.xml
  # ZhiHu:
  # Twitter:
  # Weibo:

# analytics
google_analytics:
baidu_analytics:

# mathjax
fancybox: true

# mathjax
mathjax: true

# echarts
echarts: true

# busuanzi
busuanzi: true

# mermaid
mermaid:
  enable: true
  # Available themes: default | dark | forest | neutral
  theme: default

# giscus
giscus:
  enable: false
  repo: 
  repo_id: 
  category: 
  category_id: 
  mapping: 
```


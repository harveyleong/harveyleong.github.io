## 设置Jekyll环境（Archlinux）

pacman -S ruby

在~/.bashrc中添加以下代码
PATH="$(ruby -e 'print Gem.user_dir')/bin:$PATH"

gem install jekyll
gem install bundler


## 项目结构

master分支存放静态网页，source分支存放jekyll源代码，theme分支存放主题文件。
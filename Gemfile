source "https://rubygems.org"

gem "jekyll", "4.3.2"

# 显式添加 Sass 转换器，解决 configure_sass 报错
gem "jekyll-sass-converter", "~> 2.0"

group :jekyll_plugins do
  gem "jekyll-remote-theme"
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-include-cache"
end

# 既然你用的是 just-the-docs，本地也装一个实体包通常能解决 remote 带来的兼容问题
gem "just-the-docs"
source "https://rubygems.org"

# 使用 GitHub Pages 兼容的 Jekyll
gem "github-pages", group: :jekyll_plugins

# 插件
group :jekyll_plugins do
  gem "jekyll-feed"
end

# Windows 和 JRuby 特定依赖
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# 提高 Windows 上文件监控性能
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# 锁定 http_parser.rb 版本以兼容 JRuby
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

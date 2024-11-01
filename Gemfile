source "https://rubygems.org"

# Use the GitHub Pages gem to ensure compatibility
gem "github-pages", group: :jekyll_plugins

# Additional plugin
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby dependencies
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Directory watcher for Windows
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# HTTP parser for JRuby
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

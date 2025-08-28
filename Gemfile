source "https://rubygems.org"

# Jekyll version to use
gem "jekyll", "~> 4.3.4"

# Theme
gem "minima", "~> 2.5"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby platform fixes
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# JRuby http_parser fix
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Ruby 3.4+: stdlib gems must be declared explicitly
gem "webrick"   # needed for `jekyll serve`
gem "csv"
gem "base64"
gem "logger"

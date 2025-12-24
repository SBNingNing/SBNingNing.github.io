source "https://rubygems.org"

# GitHub Pages recommended bundle to match production
# Ref: https://docs.github.com/pages/setting-up-your-github-pages-site-locally-with-jekyll

gem "github-pages", group: :jekyll_plugins

# Ruby 3+ needs webrick for `jekyll serve`
gem "webrick", "~> 1.8"

# Windows helpers
platforms :mingw, :mswin, :x64_mingw, :jruby do
  gem "tzinfo-data"
  gem "wdm", ">= 0.1.0"
end

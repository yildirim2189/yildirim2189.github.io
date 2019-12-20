# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }
gem "jekyll"
gem "github-pages", group: :jekyll_plugins
# gem "rails"


# Auto generation for Windows
gem 'wdm', '>= 0.1.0' if Gem.win_platform?

# Plugins
group :jekyll_plugins do
 gem "jekyll-feed"
 gem "jekyll-sitemap"
 gem "jekyll-seo-tag"
end
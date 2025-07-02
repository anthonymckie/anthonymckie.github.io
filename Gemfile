source "https://rubygems.org"

# GitHub Pages gems
gem "github-pages", group: :jekyll_plugins

# Jekyll plugins
gem "jekyll-feed", "~> 0.12"

# INTENTIONALLY VULNERABLE - for testing Dependabot
# This version of nokogiri has known security vulnerabilities
gem "nokogiri", "1.10.0"

# This version of rack has vulnerabilities  
gem "rack", "2.0.8"

# Add some other potentially outdated gems
gem "activesupport", "5.2.0"

group :jekyll_plugins do
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Development and testing
group :development, :test do
  gem "html-proofer"
end
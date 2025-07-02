source "https://rubygems.org"

# Specify Ruby version for consistency
ruby "3.1.7"

# GitHub Pages - this pulls in Jekyll and other dependencies
gem "github-pages", "~> 228", group: :jekyll_plugins

# INTENTIONALLY VULNERABLE GEMS (for testing Dependabot)
# These are additional gems that won't conflict with github-pages
gem "json", "2.3.0"        # Has known vulnerabilities in older versions
gem "loofah", "2.12.0"     # Has XSS vulnerabilities in this version  
gem "addressable", "2.7.0" # Has ReDoS vulnerability

# Jekyll plugins (compatible with github-pages)
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Development and testing
group :development, :test do
  gem "html-proofer", "~> 4.0"
  gem "bundler-audit"
end
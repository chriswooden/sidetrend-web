source "https://rubygems.org"

# Use the GitHub Pages gem to ensure compatibility with GitHub Pages
gem "github-pages", "~> 232", group: :jekyll_plugins

# Additional Jekyll plugins (ensure they're supported by GitHub Pages)
group :jekyll_plugins do
  gem "jekyll-environment-variables" # Ensure this is compatible
  gem "jekyll-feed", "~> 0.12"       # Default GitHub Pages plugin
  gem "jekyll-paginate"              # Supported plugin
  gem "jekyll-sitemap"               # Supported plugin
end

# Use the GitHub Pages default Markdown parser
gem "kramdown-parser-gfm" # Required for GitHub Pages Markdown rendering
# If you do not have OpenSSL installed, change
# the following line to use 'http://'
source 'https://rubygems.org'
ruby '2.3.3'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# For faster file watcher updates on Windows:
gem 'wdm', '~> 0.1.0', platforms: [:mswin, :mingw]

# Windows does not come with time zone data
gem 'tzinfo-data', platforms: [:mswin, :mingw, :jruby]

# Middleman Gems
gem "middleman", "~> 4.1"
gem "middleman-blog"
gem 'middleman-livereload'

# Sprockets
gem "middleman-sprockets"

# Markdown support
gem 'redcarpet', '~> 3.3', '>= 3.3.3'

# For feed.xml.builder
gem "builder", "~> 3.0"

# For post summaries
gem "nokogiri"

gem 'font-awesome-middleman'
gem "middleman-favicon-maker", "~> 4.0"

# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'

source "https://rubygems.org"

gem 'sqlite3', '~> 1.3.8', :platforms => :ruby

gem 'jruby-openssl', :platforms => :jruby
gem 'activerecord-jdbcsqlite3-adapter', :platforms => :jruby

gem 'rubysl', :platforms => :rbx
gem 'racc', :platforms => :rbx

gem 'pry'

# ported from paperclip.gemspec
gem 'activemodel', '>= 3.2.0'
gem 'activesupport', '>= 3.2.0'
gem 'cocaine', '0.5.5'
gem 'mime-types', '~> 1.16'
gem 'mimemagic', git: 'https://github.com/saatchiart/mimemagic', branch: 'restore-030'

# Hinting at development dependencies
# Prevents bundler from taking a long-time to resolve
group :development, :test do
  gem 'mime-types', '~> 1.16'
  gem 'builder'
  gem 'rubocop', require: false
end

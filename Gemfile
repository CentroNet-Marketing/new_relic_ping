source "http://rubygems.org"

# Declare your gem's dependencies in new_relic_ping.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

group :development, :test do
  gem "coveralls", :require => false

  # for CRuby, Rubinius, including Windows and RubyInstaller
  gem "sqlite3", :platform => [:ruby, :mswin, :mingw]

  # for JRuby
  gem "jdbc-sqlite3", :platform => :jruby
  gem "activerecord-jdbcsqlite3-adapter", :platform => :jruby
end

# jquery-rails is used by the dummy application
gem "jquery-rails"

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use debugger
# gem 'debugger'

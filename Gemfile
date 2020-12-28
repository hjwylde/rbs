source "https://rubygems.org"

# Specify your gem's dependencies in rbs.gemspec
gemspec

# Development dependencies
gem "rake"
gem "test-unit"
gem "test-unit-rr"
gem "rspec"
gem "racc"
gem "rubocop"
gem "rubocop-rubycw"
gem "json"
gem "json-schema"
gem 'stackprof'
gem "goodcheck"
gem "dbm"

# Test gems
gem "rbs-amber", path: "test/assets/test-gem"

group :ide, optional: true do
  gem "ruby-debug-ide"
end

group :minitest do
  gem "minitest"
end

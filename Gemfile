source 'https://rubygems.org'

gemspec

group :development do
  gem 'simplecov', '~> 0.9.1' if RUBY_VERSION > '1.8.7'
end

if File.exists? "#{__FILE__}.local"
  eval(File.read("#{__FILE__}.local"), binding)
end

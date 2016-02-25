source 'https://rubygems.org'

group :rake do
  gem 'rake'
  gem 'tomlrb'
end

group :lint do
  gem 'foodcritic', '~> 5.0'
  gem 'rubocop', '~> 0.34'
end

group :unit do
  gem 'berkshelf',  '~> 4.0'
  gem 'chefspec',   '~> 4.4'
end

group :kitchen_common do
  gem 'test-kitchen', '~> 1.4', git: 'https://github.com/mwrock/test-kitchen', branch: 'winrm-fs'
  gem 'winrm', '~> 1.6'
  gem 'winrm-fs', '~> 0.3'
end

group :kitchen_vagrant do
  gem 'kitchen-vagrant', '~> 0.19'
end

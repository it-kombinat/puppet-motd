source 'https://rubygems.org'

group :development, :test do
  gem 'puppetlabs_spec_helper', '0.10.1', :require => false
  gem 'rspec-puppet', '2.0.1', :require => false
  gem 'puppet-lint-strict_indent-check', '2.0.1', :require => false
  gem 'metadata-json-lint', :require => false
end

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end

if facterversion = ENV['FACTER_GEM_VERSION']
    gem 'facter', facterversion, :require => false
else
    gem 'facter', :require => false
end

# vim:ft=ruby


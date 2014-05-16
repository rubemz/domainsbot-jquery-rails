# encoding: utf-8
require 'rubygems'
require 'bundler'
require_relative 'lib/domainsbot-jquery-rails/version'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://guides.rubygems.org/specification-reference/ for more options
  gem.name = "domainsbot-jquery-rails"
  gem.homepage = "http://github.com/rubemz/domainsbot-jquery-rails"
  gem.license = "MIT"
  gem.summary = %Q{domainsbot-jquery plugin packaged as a Rails engine}
  gem.description = %Q{domainsbot-jquery plugin packaged as a Rails engine}
  gem.email = "rubem.nakamura@gmail.com"
  gem.authors = ["Rubem Nakamura"]
  gem.version = DomainsbotJqueryRails::VERSION
  # dependencies defined in Gemfile
end
Jeweler::RubygemsDotOrgTasks.new

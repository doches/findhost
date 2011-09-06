require 'rubygems'
require 'bundler'
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
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "findhost"
  gem.homepage = "http://github.com/doches/findhost"
  gem.license = "CDL"
  gem.summary = %Q{Flail around on the network, looking for a machine we can use}
  gem.description = %Q{Locate a host into which we can SSH by inspecting `~/.ssh/known_hosts`}
  gem.email = "doches@texasexpat.net"
  gem.authors = ["Trevor Fountain"]
  # Include your dependencies below. Runtime dependencies are required when using your gem,
  # and development dependencies are only needed for development (ie running rake tasks, tests, etc)
  #  gem.add_runtime_dependency 'jabber4r', '> 0.1'
  #  gem.add_development_dependency 'rspec', '> 1.2.3'
end
Jeweler::RubygemsDotOrgTasks.new
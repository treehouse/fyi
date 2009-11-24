require 'rake' 

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = 'fyi'
    gemspec.summary = 'Be informed about task execution.'
    gemspec.email = 'boss@airbladesoftware.com'
    gemspec.homepage = 'http://github.com/airblade/fyi'
    gemspec.authors = ['Andy Stewart']
    gemspec.add_dependency('pony')
    gemspec.add_dependency('open4')
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end

require 'rubygems'
require 'fileutils'

rubyforge_name = "ultraviolet"

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "hyperbolist-ultraviolet"
    gemspec.summary = "Ultraviolet is a syntax highlighting engine"
    gemspec.description = "Ultraviolet is a syntax highlighting engine based on Textpow. Since it uses Textmate syntax files, it offers out of the box syntax highlighting for more than 50 languages and 20 themes."
    gemspec.email = "hyperbolist@gmail.com"
    gemspec.homepage = "http://github.com/hyperbolist/ultraviolet"
    gemspec.authors = ["Eric Sherman"]
    gemspec.add_dependency('oniguruma', '>= 1.1.0')
    gemspec.add_dependency('textpow', '>= 0.9.0')
    Jeweler::GemcutterTasks.new
  end
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end

begin
   desc 'Create MaMa documentation'
   task :mama => :clean do
      system "mm -c -t refresh -o manual mm/manual.mm"
   end
   
rescue LoadError => e
   desc 'Run the test suite.'
   task :test do
      system "ruby -Ibin:lib:test test_#{rubyforge_name}.rb"
   end
end

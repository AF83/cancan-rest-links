begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "cancan-rest-links"
    gem.summary = %Q{Rest link helpers for CanCan}
    gem.description = %Q{Guard your links with permissions}
    gem.email = "kmandrup@gmail.com"
    gem.homepage = "http://github.com/kristianmandrup/cancan-rest-links"
    gem.authors = ["Kristian Mandrup"]
    gem.add_development_dependency "rspec", "~> 2.0.0"
    gem.add_dependency 'cancan', "~> 1.3"
    gem.add_dependency 'require_all', "~> 1.1"
    gem.add_dependency 'sugar-high', "~> 0.1" 
    # gem.add_dependency 'rails3_plugin_toolbox', "~> 0.3"  
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end

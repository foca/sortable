require 'rubygems'
gem 'hoe', '>= 2.1.0'
require 'hoe'
require 'fileutils'
require './lib/sortable'

Hoe.plugin :newgem

# Generate all the Rake tasks
# Run 'rake -T' to see list of generated tasks (from gem root directory)
$hoe = Hoe.spec 'sortable' do
  self.developer 'Ben Scofield', 'ruby@turrean.com'
  self.rubyforge_name       = 'sortable-object'
end

require 'newgem/tasks'
Dir['tasks/**/*.rake'].each { |t| load t }

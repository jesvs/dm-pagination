
$:.unshift 'lib'
require 'dm-pagination'
require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new "dm-pagination", DataMapper::Pagination::VERSION do |p|
  p.author = "TJ Holowaychuk"
  p.email = "tj@vision-media.ca"
  p.summary = "DataMapper Pagination"
  p.url = "http://github.com/visionmedia/dm-pagination"
  p.runtime_dependencies = ['dm-core >=0.10.1']
end

Dir['tasks/**/*.rake'].sort.each { |f| load f }
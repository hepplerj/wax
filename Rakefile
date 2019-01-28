# load gems with rake tasks for use with `bundle exec rake`
gems = ['wax_tasks', 'wax_annotate']
gems.each do |gem|
  gem_dir = Gem::Specification.find_by_name(gem).gem_dir
  Dir.glob("#{gem_dir}/lib/tasks/*.rake").each { |r| load r }
end

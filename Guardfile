# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'sprockets',:root_file   => 'app/assets/javascripts/application.js', :minify => true, :destination => 'public/javascripts', :asset_paths => ['app/assets/javascripts'] do
  #watch 'app/assets/javascripts/'
  watch (%r{^app/assets/javascripts/(.+)\.js$})
end

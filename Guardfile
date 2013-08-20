# A sample Guardfile
# More info at https://github.com/guard/guard#readme



# minifies using Uglifier and creates output file in same directory as source file 

guard 'sprockets',:root_file   => 'app/assets/javascripts/application.js', :minify => true, :destination => 'app/assets/javascripts', :asset_paths => ['app/assets/javascripts'] do
  watch (%r{^app/assets/javascripts/(.+)\.js$})
end



# without minimization, output into public/javascripts/ 

#guard 'sprockets',:root_file   => 'app/assets/javascripts/application.js', :minify => false, :destination => 'public/javascripts', :asset_paths => ['app/assets/javascripts'] do
#  watch (%r{^app/assets/javascripts/(.+)\.js$})
#end
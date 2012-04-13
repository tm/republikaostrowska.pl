# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'slim', :slim => { :pretty => true } do
  watch(%r'^.+\.slim$')
end

guard 'sass', :output => "assets/css", :style => :compressed do
  watch(%r{^assets/scss/(.+\.scss)$})
end

guard 'compass', :configuration_file => "compass.config" do
  watch(%r{stylesheets/.+\.s[ac]ss})
end

guard 'livereload' do
  watch(%r{^public/.+\.(css|js|html)})
  watch(%r{views/.+\.(erb|haml|rb)})
end

# # still doesn't work too well, this smushes files twice!
# guard :shell do
#   watch(%r{^public/.+\.(png|jpg)}) do |file|
#     n file[0], "smushing", :pending
#     %x(smusher #{file[0]})
#   end
# end
# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard :rspec, cmd: 'rspec --color --format doc' do
  watch(%r{^spec/.+_spec\.rb$})
  watch(%r{^lib/(.+)\.rb$})     { |m| "spec/lib/#{m[1]}_spec.rb" }
  watch('lib/gosu_texture_packer.rb')  { 'spec' }
  watch('spec/spec_helper.rb')  { 'spec' }
end


# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard :rspec do
  watch(%r{spec/.*/.*\.rb})  { 'spec' }
  watch('spec/spec_helper.rb')  { 'spec' }
  watch(%r{src/.*\.(c|h)})  { 'spec' }
end


guard 'bundler' do
  watch('Gemfile')
  # Uncomment next line if Gemfile contain `gemspec' command
  # watch(/^.+\.gemspec/)
end
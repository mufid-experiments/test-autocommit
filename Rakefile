task :default do
  require 'yaml'
  require 'json'
  yml = YAML.load_file('test.yml')
  json = JSON.pretty_generate(yml)
  File.write('test.json', json)
end


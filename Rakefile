desc "Download site from burundi.dev"
task :download do
  system 'rm -rf index.html assets robots.txt'
  `wget -r -P .. burundi.dev`
end


task :build do 
  sh "parse-hocon hocon/style.conf --output htdocs/style.json"
  sh "gl-style-validate htdocs/style.json"
end


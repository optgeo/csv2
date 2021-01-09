task :default do
  sh "parse-hocon hocon/style.conf > docs/hocon.json"
  sh "gl-style-validate docs/hocon.json"
end

task :host do
  sh "budo -d docs"
end

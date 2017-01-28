guard 'livereload', host: '0.0.0.0', port: ENV['WAGON_LIVERELOAD_PORT'] || 35729, grace_period: 0.5 do
  watch(%r{app/content_types/.+\.yml$})
  watch(%r{app/views/.+\.liquid})
  watch(%r{config/.+\.yml$})
  watch(%r{data/.+\.yml$})
  watch(%r{public/((stylesheets|javascripts)/(.+\.(css|js))).*}) { |m| "/#{m[1]}" }
end

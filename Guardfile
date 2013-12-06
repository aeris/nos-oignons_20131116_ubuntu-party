require 'sass'
require 'coffee_script'

ignore %r{.*\.kate-swp.*}
ignore %r{.*\.new}

guard :haml, run_at_start: true, haml_options: { format: :xhtml } do
	watch %r{.*\.haml}
end

guard :livereload, apply_css_live: false, override_url: false  do
	watch %r{.*\.html}
	watch %r{img/.*}
end

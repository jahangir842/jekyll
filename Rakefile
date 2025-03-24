require 'html-proofer'

task :test_html do
  HTMLProofer.check_directory('./_site', { :allow_missing_href => true }).run
end
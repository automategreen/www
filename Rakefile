require 'html-proofer'

task :test do
  sh "bundle exec jekyll build"
  HTMLProofer.check_directory("./_site", {
    :allow_hash_href => true,
    :url_swap => {%r{https://www.automategreen.com(/.*)} => "\\1"},
    :check_html => true
  }).run
  # HTML::Proofer.new("./_site", {:href_ignore => ["#"], :href_swap => {%r{https://www.automategreen.com(/.*)} => "\\1"}}).run
end
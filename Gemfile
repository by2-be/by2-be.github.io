# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'
ruby "2.3.3"
gem "rake"

gem "middleman", "~>3.2.1"

# Live-reloading plugin
gem "middleman-livereload", "~> 3.1.0"
gem "rack-contrib"
gem "puma"

# css
gem "bootstrap-sass"

# image handling
gem "chunky_png"
gem "oily_png"

# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]

# Cross-templating language block fix for Ruby 1.8
platforms :mri_18 do
  gem "ruby18_source_location"
end

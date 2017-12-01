ruby '2.4.2'

# If you do not have OpenSSL installed, update
# the following line to use "http://" instead
source 'https://rubygems.org' do
  # Version specifiers:
  #   ~> updates y in 1.0.y (recommended)
  #   ~> updates x in 1.x
  #   => updates x and y in 1.x.y
  #   <, >, <=, >=
  #   =  doesn't update
  #   No version, updates to latest (can be risky)
  gem "middleman",                  "~> 4.2.1"
  gem "middleman-livereload",       "~> 3.4.6"
  gem 'middleman-deploy',           "~> 2.0.0.pre.alpha"
  gem "slim",                       "~> 3.0.9"
  # gem "middleman-deploy",           "~> 1.0"

  # For faster file watcher updates on Windows:
  gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]

  # Windows does not come with time zone data
  gem "tzinfo-data", platforms: [:mswin, :mingw]
end

  # Create the folder
  
  509  jeweler geometry-mf --rspec --create-repo
  510  cd geometry-mf/
  508  bundle
  504  subl .
  
  RAKEFILE edit the following
  gem.summary = %Q{Checks triangle info}
  gem.description = %Q{Checks difference shapes info}
  GEMFILE replace last gem with
  gem "simplecov"
  FILES
  edit FOO_spec.rb and FOO.rb
  

  505  bundle

  507  rake version:write MAJOR=0 MINOR=1 PATCH=0
  512  rspec spec
  513  rake install
  514  gem list
  520  git add .
  521  git commit -m "created a gem for geometry"
  523  rake release

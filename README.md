ruby_project_template
=====================

OVERALL
- Create a Gemfile 
  - touch Gemfile
  - add: source "https://rubygems.org"
- Create a .gitignore
  - touch .gitignore
  - add the following files if necessar
    - *.gem
    - *.rbc
    - .bundle
    - .config
    - InstalledFiles
    - lib/bundler/ma
    - pkg
    - rdoc
    - spec/reports
    - test/tmp
    - test/version_tmp
    - tmp
    - .DS_STORE
    - .yardoc
    - _yardoc
    - doc/
- Initialize a Git repo
  - git init
- Create or fork repo on Github
  - On github create or fork a repo. Add this repo as your origin
  - git remote add origin PASTE SSH
- Create a lib directory to hold code
  - mkdir lib
RSPEC
  - Add Rspec to your Gemfile
    - gem "rspec"
  - Run in folder in console to create .rspec and .rspec_helper 
    - rspec --init
  - Create a spec/FOO_spec.rb file
    - touch spec/FOO_spec.fb
    - add the following to the FOO_spec.rb
      - require "spec_helper"
      - require_relative "../lib/FOO.rb"
      - describe FOO do
      - end
TRAVIS

SIMPLECOV
PRY
GUARD

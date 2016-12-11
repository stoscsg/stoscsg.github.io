![Build Status](https://api.travis-ci.org/stoscsg/stoscsg.github.io.svg)

# Build Instructions.github.io
Website for STOSC


1. [Setup](https://labs.sverrirs.com/jekyll/1-ruby-and-devkit.html) environment on Windows 
2. Install [RubyDevKit](http://rubyinstaller.org/downloads/)
3. `ruby dk.rb init`
4. `ruby dk.rb review`
3. Set PATH to Ruby and RubyDevKit
4. Install Bundler: `gem install jekyll bundler`
5. Setup [Travis](https://jekyllrb.com/docs/continuous-integration/) and add travis file with html-proofer
6. OPTIONAL: Install HTML proofer gem if needed to test site and links `gem install html-proofer`
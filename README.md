![Build Status](https://api.travis-ci.org/stoscsg/stoscsg.github.io.svg) ![Security Warnings](https://hakiri.io/github/stoscsg/stoscsg.github.io/master.svg) ![Code Climate](https://codeclimate.com/github/stoscsg/stoscsg.github.io/badges/gpa.svg)
# Build Instructions.github.io
Website for STOSC (Beta)

## SETUP
There are 3 ways I've tried to setup the environment:

### Option 1
1. [Install Chocolatey](https://chocolatey.org/docs/installation#installing-chocolatey)
2. Install the needed chocolatey packages
    ```dos
    choco install ruby -y
    gem install jekyll bundler jekyll-paginate html-proofer
    ```
3. Navigate to the cloned repo (this one) and run: `bundle exec jekyll serve`


### Option 2
1. [Setup](https://labs.sverrirs.com/jekyll/1-ruby-and-devkit.html) environment on Windows. Install Ruby and the Ruby DevKit
2. In RubyDevKit, `ruby dk.rb init`  & `ruby dk.rb review` & `ruby dk.rb install`
3. Set PATH to Ruby and RubyDevKit `set PATH=%PATH%;D:\RubyDevKit;D:\Ruby23-x64\bin`
4. Install Bundler: `gem install jekyll bundler jekyll-paginate html-proofer`
5. Navigate to site folder and run site: `bundle exec jekyll serve`
5. Setup [Travis](https://jekyllrb.com/docs/continuous-integration/) and add travis file with html-proofer
6. OPTIONAL: Install HTML proofer gem if needed to test site and links `gem install html-proofer`

### Option 3
Follow instructions per [this](https://jekyllrb.com/docs/windows/) link


## RUN

Serve pages:

```
bundle exec jekyll serve
```
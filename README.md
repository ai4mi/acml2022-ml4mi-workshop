# ML4MI Workshop at ACML 2022

Workshop website: https://ai4mi.github.io/acml2022-ml4mi-workshop/

Steps to run/develop the website on localhost (mac), 

* Install rbenv
<pre><code>$ brew install rbenv
$ vim ~/.bash_profile 
  >> Add eval "$(rbenv init -)" to ~/.bash_profile
$ source ~/.bash_profile</code></pre>

* Install Ruby
<pre><code>Check if Ruby is already installed, 
$ ruby -v

If version < 2.7.1, uninstall Ruby,
$ brew uninstall ruby

Check available Ruby versions and install the latest, 
$ rbenv install -l
$ rbenv install 3.1.2
$ rbenv global 3.1.2
$ ruby -v 
  >> My version: ruby 3.1.2p20</code></pre>

* Working with Gems
<pre><code>$ gem -v
  >> My version 3.3.7
$ echo "gem: --no-document" > ~/.gemrc
$ gem install jekyll bundler</code></pre>

* Build the site and make it available on a local server
<pre><code>$ bundle install
$ bundle exec jekyll serve</code></pre>

Useful links:
* [Ruby installation guidelines](https://www.ruby-lang.org/en/downloads/)
* [Ruby installation with Rbenv on macOS](https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-with-rbenv-on-macos)
* [Source template](https://github.com/carpentries/training-template)

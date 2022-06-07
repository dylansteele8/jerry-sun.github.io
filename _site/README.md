# Personal website

Including tabs for:

* Writing
* About
* Travels
* Search
* RSS

May also include future tabs for things such as books read and other miscellaneous topics at a later date.

Thanks for visiting.

## Developing

The instructions for developing assume you are using MacOS and have [Homebrew](https://brew.sh/) installed.

```sh
# Install a separate version of Ruby v2
brew install ruby@2
# Add `export PATH="/usr/local/opt/ruby@2.7/bin:$PATH"` to .bashrc

# Install jekyll and bundler packages
gem install jekyll bundler

# Install project dependencies
bundle install

# Serve site locally
bundle exec jekyll serve
```

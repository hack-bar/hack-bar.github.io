# Installation Instructions
## Deploy locally
### Using RVM
#### Dependencies
 - rvm
 - cmake
 - libssl-1.0.1: `rvm pkg install openssl`
#### Usage
```
rvm install ruby-2.7.4 --with-openssl-dir=$HOME/.rvm/usr    # needs login shell to work
rvm use 2.7.4
rvm gemset create pages
rvm use 2.7.4@pages
bundle install
bundle exec jekyll serve --livereload
```


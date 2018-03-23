# gem_of
Gem testing gems, rake tasks

## locally install this gem
you can't put this in your Gemfile, because we need to use it to form your Gemfile
```
gem install --local gem_of
```

## In your Gemfile
```
require 'gem_of'

eval(GemOf.gems, binding)
```

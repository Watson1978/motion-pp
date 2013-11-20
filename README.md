# motion-pp

Pretty-printer for RubyMotion objects.

## Installation

Add this line to your application's Gemfile:

    gem 'motion-pp'

And then execute:

    $ bundle

Or install it yourself as:

    $ [sudo] gem install motion-pp

## Usage


This gem can be used in Rakefile of your RubyMotion project by requiring.

    require 'motion-pp'


And then, you would write the code, like:

```ruby
  ary = Array.new(5) { {:foobar => :baz} }
  pp ary
  #=> [{:foobar=>:baz},
       {:foobar=>:baz},
       {:foobar=>:baz},
       {:foobar=>:baz},
       {:foobar=>:baz}]
```

This library provides the same APIs as standard Ruby. You could see the APIs references at http://ruby-doc.org/stdlib-1.9.3/libdoc/pp/rdoc/

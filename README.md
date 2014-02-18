# Micro Cutter

Create the base files needed for a micro gem (potentially stored in a
gist).

## Usage

Call the executable, passing a camel cased class name:

    micro-cutter ActsAsBoolean

This creates boilerplate files (overwriting any already there):

* README.md
* acts_as_boolean.gemspec
* acts_as_boolean.rb
* acts_as_boolean_spec.rb

## Using a Gist to store your MicroGem

Head to [gist.github.com](https://gist.github.com) and create a gist:

* Give it a good name

    micro-cutter YourClassName
    cd your_class_name

## Options

* `-g` Disable Gemfile creation
* `-r` Disable RSpec
* `-s` Disable Gem signing when [waxseal](https://github.com/steakknife/waxseal) is available
* `-a` git commit && push, and make a private jist is installed `gem install gist`
* `-P` make a public jist

# Credits

* **[@jkreeftmeijer](http://twitter.com/jkreeftmeijer)** for coming up with the killer MicroGem concept<br/> (http://jeffkreeftmeijer.com/2011/microgems-five-minute-rubygems/)
* **[@moutten](http://twitter.com/moutten)** for helping me through the file name handling and generally making me a better Ruby developer every day
* **[@mettaaudio](http://twitter.com/mettaaudio)** for not laughing too loudly as I hacked this together over lunch and made countless typos

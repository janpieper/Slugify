# Slugify

A slugifier that converts utf-8 latin characters to their ascii counterpart.
All non-recognized characters are removed, only lowercase alphanumerical
characters and dashes are left. Also has an option to strip away starting,
ending and double dashes.

Conversion is based on [Latin script in Unicode](http://en.wikipedia.org/wiki/Latin_characters_in_Unicode) (Wikipedia).

To use, just install it

```
gem install slugify
```

require it

```ruby
require 'slugify'
```

and use it

```ruby
"test test".slugify
```

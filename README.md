# Ruby Essentials Training #

Ruby Essentials Training course on [LinkedIn][1] by [Kevin Skoglund][2]

- Author from this repo: [Francis Rodrigues][3]

![Ruby logo](screenshots/ruby-logo.png)

## Ruby is ##

A dynamic, open source programming language with a focus on simplicity and productivity. It has an elegant syntax that is natural to read and easy to write.

```rb
# Output "I love Ruby"
say = "I love Ruby"
puts say

# Output "I *LOVE* RUBY"
say['love'] = "*love*"
puts say.upcase

# Output "I *love* Ruby"
# five times
5.times { puts say }
```

## About Ruby ##

The Ideals of Ruby’s Creator
Ruby is a language of careful balance. Its creator, Yukihiro "Matz" Matsumoto, blended parts of his favorite languages (Perl, Smalltalk, Eiffel, Ada, and Lisp) to form a new language that balanced functional programming with imperative programming.

He has often said that he is "trying to make Ruby natural, not simple," in a way that mirrors life.

Building on this, he adds:

> Ruby is simple in appearance, but is very complex inside, just like our human body1.

## Environment on Linux ##

Ruby version:

```bash
~$ ruby -v
ruby 2.1.5p273 (2014-11-13) [x86_64-linux-gnu]
```

Ruby executable path:

```bash
~$ which ruby
/usr/bin/ruby
```

## How to learn more about Ruby ##

See the References guide.

## References ##

- [Ruby installation][4]
- [Ruby Doc][9]
- [Try Ruby online][5]
- [CodeSchool - Getting Started with Ruby on Rails][6]
- [CodeCademy - Learn Ruby][7]
- [Ruby on Rails][8]

## License ##

MIT

  [1]: https://www.linkedin.com/learning/ruby-essential-training
  [2]: https://www.linkedin.com/learning/instructors/kevin-skoglund
  [3]: https://github.com/francisrod01
  [4]: https://www.ruby-lang.org/en/documentation/installation/
  [5]: http://tryruby.org/
  [6]: https://www.codeschool.com/learn/ruby
  [7]: https://www.codecademy.com/learn/learn-ruby
  [8]: http://rubyonrails.org/
  [9]: https://ruby-doc.org/

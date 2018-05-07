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
ruby-apps@debian:~$ ruby -v
ruby 2.1.5p273 (2014-11-13) [x86_64-linux-gnu]
```

Ruby executable path:

```bash
ruby-apps@debian:~$ which ruby
/usr/bin/ruby
```

## Using Ruby ##

Three ways to use Ruby:

- Single command
- Ruby file
- Interactive Ruby Shell (IRB)

### Using as a Single Command ###

Using `puts` command:

```bash
/home/ruby-apps@debian:~$ ruby -e 'puts 123'
123
/home/ruby-apps@debian:~$
```

Using `print` command:

```bash
/home/ruby-apps@debian:~$ ruby -e 'print 123'
123/home/ruby-apps@debian:~$
```

### Using as Ruby file ###

Create a `simple_file.rb` ruby file and type as below:

```rb
puts 123
print 456
puts 789
```

Let's run it:

```bash
/home/ruby-apps@debian:~$ ruby simple_file.rb
123
456789
/home/ruby-apps@debian:~$
```

### Using as an Interactive Ruby Shell (IRB) ##

IRB is a command line interface as ruby.

- Allows us to interact with code in real time
- Works like a calculator
- Great for testing code

Just run `irb` in a console and see a prompt command line waiting for a command:

```bash
/home/ruby-apps@debian:~$ irb
irb(main):001:0>
```

`irb` seems like a calculator:

```bash
/home/ruby-apps@debian:~$ irb
irb(main):001:0> 1 + 1
=> 2
irb(main):002:0>
irb(main):003:0> 45 / 9
=> 5
irb(main):004:0>
```

`puts` commands returns a `nil` value:

```bash
irb(main):004:0> puts 1 + 2
3
=> nil
irb(main):005:0>
```

`quit` command to exit it:

```bash
irb(main):005:0> quit
/home/ruby-apps@debian:~$
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

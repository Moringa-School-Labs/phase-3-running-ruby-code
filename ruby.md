# RUBY NOTES

## Comments in Ruby

- Hash sign (#) reps a comment in ruby

## Printing string output - puts and print

- Puts and prints are built-in ruby methods that prints string output on the terminal - same as console.log in JS.
  ### Difference
  - puts adds a line break at the end of the string, while print won't.

## Optional use of parenthesis in Ruby

- The use of parenthesis when invoking a methods is optional
  eg
  puts("Hello World") is same as
  puts "Hello world" // Most Preferred

## Running Ruby Application

- Enter this command in terminal
  ### ruby filename.rb eg ruby myApp.rb

## Inspecting data with p and pp

- Helpful for inspecting other kinds of data that aren't strings.

  ### eg array

  - When you use puts with something that isn't a string, Ruby will coerce the data to a string by calling the .to_s method.

  #### p

  - p [1,2,3] is equivalent to calling puts [1,2,3].inspect
  - Outputs data in a nicer format by calling .inspect method on our data

  #### pp - pretty-print

  - pretty prints objects data or nested data by calling .pretty_inspect method

## Ruby IRB - Interactive Ruby

- IRB is tool for running Ruby REPL(Read-Evaluate-Print-Loop) in the terminal, which provides similar functionality to the browser console.
- IRB is a great way to quickly test out some code, or check syntax, without needing to run the entire application.
- To run IRB type $irb into the terminal. It gives you a prompt where you can run ruby code.
- first line is the output, second is Return value eg Nil(null in js)
  ### puts method always returns nil

## Naming Variables - snake case

- use underscore to separate words in variables eg my_num unlike camel case in js.
- Exit IRB by typing exit.

## Running RSpec Tests
- RSpec library for testing your Ruby code.
- RSpec is a Ruby gem (the Ruby equivalent of a npm package) that provides a domain-specific language, or DSL, that makes it very nice way to write tests.
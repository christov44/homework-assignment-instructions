## Lesson 02 Homework Assignment


### Code Reading

Add a comment (a line starting with `#` ) before each line explaining what it does. Add a comment before the method name explaining, in plain english, what the method does. Try copying and pasting this into a ruby file and modifying it to help you figure it out. Try adding "puts" lines in at different places to see what happens.


```ruby

  def fizzbuzz(num)
    case
    when num % 15 == 0 then "FizzBuzz"
    when num % 3  == 0 then "Fizz"
    when num % 5  == 0 then "Buzz"
    else num
    end
  end

  def fizz_buzz_to(limit)
    1.upto(limit).each do |num|
      puts fizzbuzz(num)
    end
  end

```

### Fix Broken Code

The following code contains some errors and some coding ettiquette issues. Fix and refactor the code so that it works and is more clear.

```ruby

def area_of_triangle(b, h)
  puts b x height / 2
end

base = 7
height = 6

puts area_of_triangle(height, height)

```

### Coding

1. Write a method called `add` that does the following:
  - takes two parameters and adds them together returning the result. For example `add(1, 2)` should return `3`. 
  - Add a line that calls your add function with two values, stores the result in a variable, and then prints the result to the screen.

2. Write a method, `join_strings` that does the following: 
  - takes two string values as parameters and joins them together with a space in between, returning the result. 
  - For example `join_strings("hello", "dolly")` should return `"hello dolly"`.

3. Write a method called 'old_enough_to_vote?' that does the following:
  - Takes a integer year as a parameter and returns a "yes" if a person born in that year is old enough to vote or returns "no" if the person is not old enough to vote


### Additional Weekend Assignment

- Complete RubyMonk's **Ruby Primer** interactive tutorial found [here](https://rubymonk.com/learning/books/1-ruby-primer)
- **Install Rails** - follow the instructions found [here](http://installrails.com/)

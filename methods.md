## Methods
We will use methods to get information about our collections.  You have already seen that we can ask a collection to how big it is, where it starts and what the max value is.

We will use methods to do our math, too -- `+`, `*` and other operators are methods, but to make arithmetic easier in Ruby these operators don't need the `.` like methods usually do.

(You may use the `.` but I will not; I will not use the `.`)
```ruby
a = 3

a + 7

a.+7

a. + 7

a      .  +                           7                 -2
```

### Method parameters
Sometimes a method wants you to provide some information, sometimes it doesn't.  When you are doing most arithmetic operations you need to supply a parameter.  When you type 
```ruby
2 + 5
```
you are telling Ruby
```ruby
2.+(5)
```
or
"Hey 2!  Add five to yourself and tell me what you get!"

Here are some non-arithmatic questions you can ask a `Range` to tell you about itself.  These don't require any parameters.
```ruby
two_through_eight = (2..8)

two_through_eight.min

two_through_eight.max

two_through_eight.first

two_through_eight.last

two_through_eight.size
```

But there are some questions we can ask that won't be answered as we may expect
```ruby
two_through_eight.start
NoMethodError: undefined method `start' for 2..8:Range

two_through_eight.favorite_food
NoMethodError: undefined method `favorite_food' for 2..8:Range
```




## Collections 

Collections are simply groups of things.  You probably have collections of things that are related.  The collections we're going to talk about are collections of numbers.  We will use collections so we can type less code.

We will *not* be typing sequences of numbers.  We *will* use `Range`s instead.  A `Range` is a type of collection

> A Range represents an interval—a set of values with a beginning and an end. 
 - http://ruby-doc.org/core-2.2.0/Range.html

We create a `Range` by supplying a starting number and an ending number
```ruby
(1..10)

(1..10).size

(1..10).first

(1..10).last
```

`Range`s don't have to start at 0:
```ruby
(-7..13)

(-7..13).size

(-7..13).first

(-7..13).last
```

You can use variables to represent anything in Ruby, including a `Range`:

```ruby
two_through_eight = (2..8)

two_through_eight.min

two_through_eight.max

two_through_eight.minmax
```

## Enumerators
Enumerators allow you to go through each value in a collection and call a method on it, or send it as a parameter to another method, or do both or do neither.  The place where we do the thing (or don't do the thing) is between the `do` and the `end`.

This does nothing:
```ruby
(2..7).each do

end
```

This calls the multiply method on the number three using each of the values in our collection as a parameter, then it calls the puts method with the result of the operation so that we can see what happened:
```ruby
(2..7).each do |num|
  puts 3 * num
end
```

This calls the add method on each value in our collection using that value as a parameter (*mind blown*), then it calls the puts method with the result of the operation so that we can see what happened:
```ruby
(2..7).each do |num|
  puts num + num
end
```

Cool, huh?  Here's how you can use an enumerator to remind yourself of your times table for the number eight:
```ruby
(1..10).each do |num|
  puts num * 8
end
```




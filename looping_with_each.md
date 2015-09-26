End goal:

```ruby
1..9).each do |num|
  puts "#{num} * #{tt} = #{num * tt}"
end

def tables(val, limit=9)
  (1..limit).each do |num|
    puts "#{num} * #{val} = #{num * val}"
  end
end
```
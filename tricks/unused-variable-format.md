### Unused variable format

```ruby
  [
    ['Someone', 41, 'another field'],
    ['Someone2', 42, 'another field2'],
    ['Someone3', 43, 'another field3']
  ].each do |name,_,_|
    p name
  end

# Result:
# "Someone"
# "Someone2"
# "Someone3"

```

[View Source](source_code/unused_variable_format.rb)


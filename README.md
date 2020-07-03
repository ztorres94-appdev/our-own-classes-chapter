# Ruby Practice

Run your Ruby file by typing `ruby ` and then the name of the file you want to run in the Terminal.

If we want to run `class_person.rb`, we can write the command:

```bash
ruby class_person.rb
```

To re-run this command, you can use the UP and DOWN arrow keys to look at the history of commands you've run in a Terminal.

## Our own classes

### class_person.rb
Define a class Person with:

 - An attribute first_name
 - An attribute last_name
 - An attribute birthdate (we just assign a string to this attribute, e.g. "April 19, 1987")
 - An instance method, full_name, that puts first_name and last_name together
 - An instance method, age, that calculates the number of years between today and birthdate

These methods should **return** an values; they shouldn't print anything to the terminal.

Example
```ruby
dev = Person.new
dev.first_name = "James"
dev.last_name = "Baldwin"
dev.birthdate = "November 16, 1953"
dev.full_name # => "James Baldwin"
dev.age # => 67
```

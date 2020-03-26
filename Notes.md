Similar to arrays

array = ["dog","cat","fox"]
hash = {"key" => "value","another_key" => "another_value"}
(like a dictionary)

keys can be any type of data: string / ints / symbols / etc
only use each key once
duplicating keys overwrites the existing key
each K/V pair is unique

Create Hashes

my_hash = {}
pets = {"cat" => "Maru", "dog" => "spot", "fish" => "toby"}

Retrieving Data from Hashes

Similar to array but instead of index in [] we use key in [] (with quotes) ex: pets["cat"]


Adding Key/Values to Hashes

Instead of << we use bracket equals
person{"hometown"} = "Massena, NY"
hash["new_key"] = "new value"

Symbols
similar to strings but symbols cant be changed, they are unique

:symbol
:i_am_a_symbol

Strings are mutable
Steven".chomp("n") => "Steve"
```
"name = "Steven"
same_as_name = "Steven"

name.object_id == same_as_name.object_id
  #=> false"
```

Symbols are immutable
```
name = :steven
same_as_name = :steven
name.object_id == same_as_name.object_id
  #=> true
```

We use symbols as hash keys because they use less memory than strings

flatiron_school = {:instructor => "Isaac Newton"}
flatiron_school = {instructor: "Isaac Newton"}
^^ are the same

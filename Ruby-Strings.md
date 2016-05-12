# Ruby Strings

## Basics:

- Strings are a series of characters 'strung' together between quotes.
- Single or double quotes can be used to create strings in Ruby.
- Ruby does some extra evaluation on strings that are created with double quotes, such as:

  - Escaping characters: `\n`, `\t`, `\s`
  - Using variables and expressions inside: `#{variable or expression}`

- Strings with single quotes are rendered as they are, without any special considerations.

## Examples:

```ruby
"Hello World"
# is equivalent to:
'Hello World'
```

```ruby
"This is line 1.\nAnd this is line 2."
# returns:
This is line 1.
And this is line 2.
```

```ruby
name = "Batman"
"Hello, my name is #{name}!"
# returns:
Hello, my name is Batman!
```

```ruby
# Note that for single quotes, ruby doesn't take special consideration for variables or backslashes:
'This is your name:\n#{name}'
# returns:
This is your name:\n#{name}
```

## References:

- [The official Ruby documentation for strings](http://ruby-doc.org/core-2.2.0/String.html).

## Table of Contents

1. [Ruby String Operators](Ruby-Strings-Operators)
2. [Ruby String Methods](Ruby-String-Methods)
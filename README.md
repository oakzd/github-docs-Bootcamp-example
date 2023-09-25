# Github-docs-Bootcamp-example

## Writing Good Documentation

## Codeblocks in markdown make it *really easy* for people working tech to copy,paste, and share code.
A good __Cloud Engineer__ uses codeblocks whenever possible.

Because it allows others to view your code and try to replicate what you did!

## A Ruby example (using codeblocks)

```ruby
def alternating_characters?(s)
  type = [/[aeiou]/, /[^aeiou]/].cycle

  if s.start_with?(/[^aeiou]/)
    type.next
  end

  s.chars.all? { |ch| ch.match?(type.next) }
end

alternating_characters?("ateciyu")
# true
```

## A python example (using codeblocks)
```python
# Store input numbers
num1 = input('Enter first number: ')
num2 = input('Enter second number: ')

# Add two numbers
sum = float(num1) + float(num2)

# Display the sum
print('The sum of {0} and {1} is {2}'.format(num1, num2, sum))

```

## Insert a image

![shooting stars](https://github.com/oakzd/github-docs-Bootcamp-example/assets/11877532/2b5b6705-27ec-4267-898c-09d5d18db30d)



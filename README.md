# Github-docs-Bootcamp-example

## Writing Good Documentation

## Codeblocks in markdown make it *really easy* for people working tech to copy,paste, and share code.
 *  A good __Cloud Engineer__ uses codeblocks whenever possible.

 *  Because it allows others to view your code and try to replicate what you did!

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
<img width = '200' src = "https://github.com/oakzd/github-docs-Bootcamp-example/assets/11877532/2b5b6705-27ec-4267-898c-09d5d18db30d" />

## Good Cloud engineers use codeblocks for both code and errors!
> Below is an example
```bash
$ RBENV_VERSION=2.5.0 ruby division_service.rb 5 0

Traceback (most recent call last):
	2: from division_service.rb:13:in `<main>'
	1: from division_service.rb:9:in `divide'
division_service.rb:9:in `/': divided by 0 (ZeroDivisionError)

$
```
## Step 3 - Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items.[<sup>[1]</sup>](#external-references)
- [X] Finish Step 1
- [ ] Finish Step 2
- [X] Finish Step 3

## Step 4 - Using Emjois (Optional)
> Github Flavored Markdown (GFM) Supports Emojis :exploding_head:

### Examples using a __table__

| Section 1 | Section 2 |
| :-----------: | :------------: |
| **Face** | **Sports**   |
| 😄 | 🏀   |
| 🤠 | 🏈   |

| Section 1 | Section 2 |
| :-----------: | :------------: |
| **Code** | **Emoji**   |
| `:dog:` | :dog:   |
| `:owl:` | :owl:   |

## Step 5 = how to create a table
> You can use the following format to create tables!
```md
| Section 1 | Section 2 |
| :-----------: | :------------: |
| **Code** | **Emoji**   |
| `:dog:` | :dog:   |
| `:owl:` | :owl:   |
```
GFM provides really cool formating for tables[<sup>[2]</sup>](#external-references)

## external References

Links I used
1. I used this for syntax [Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images)
2. I used this for Ruby code [Ruby Example](https://www.rubyguides.com/2019/02/ruby-code-examples/)
3. I used this for Python code [Python Example](https://www.programiz.com/python-programming/examples/add-number)
4.I used this for Ruby code [Ruby Error Example](https://www.bigbinary.com/blog/ruby-2-5-prints-backstrace-and-error-message-in-reverse-order) <sup>[1]<sup>
5. [Emoji list!](https://github.com/ikatyang/emoji-cheat-sheet#table-of-contents)
6. [Format tables](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables) <sup>[2]<sup>

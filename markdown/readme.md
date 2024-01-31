# Markdown Examples

- [unordered lists](#unordered-lists)
- [ordered lists](#ordered-lists)
- [text formatting](#text-formatting )
- code
- tables
- links
- images
- autolists
- lists

https://github.github.com/gfm/

## Unordered Lists

We can create unordered lists in GitHub Flavored Markdown using hyphens.

- red
- green
- blue
+ earth
+ air
+ fire
+ water

## Ordered Lists

Create ordered lists using the same number. Changing the number or delimiter starts a new list.

1. First
1. Second
1. Third
1) first
1) second
1) third
1. foo
2. bar
3) baz


## Text Formatting

Use an asterisk before and after to italicize.

*italics*
_italics_ (some parsers also allow underscores)

Use doulbe asterisks before and after to bold.

**bold**
__bold__ (some parsers also allow double underscores)

Use double tildes before and after to strikethrough.

~~strikethrough~~


## Code

### Inline code

You can print to the terminal using a single backtick, such as the (there is a backtick in front of the following codeblock in the markdown) `puts "hello world"` command.

### Multi line code

Use 3 backticks to print out multiple lines of code to the document, such as the code blocks shown below.

#### Without highlighting


Using the three backticks by themselves will result in no code highlighting, as shown below.

```
def hello_world
    puts 'hello world'
end
```
#### With highlighting

To display syntax highlighting, use three backticks follwed by the name of the desired programming language, such as 'ruby'

With Ruby syntax highlighting...
```ruby
def hello_world
    puts 'hello world'
end
```

With Java syntax highlighting...

```java
def hello_world
    puts 'hello world'
end
```

## Tables

| Column Heading 1 | Column Heading 2 | Column Heading 3 |
| --- | --- | --- |
| Bob | Gary | Anderson |

| First Name | Middle Name | Last Name |
| :-- | :-: | --: |
| Bob | Gary | Anderson |

## Links

To add a link within the same document, place the desired link text between square brackets, followed by parentheses and a hash symbol, which will bring up a list of the available reference points in the documents, such as headings, etc.

Example:
    Unordered Lists
    [Unordered Lists](#)

   > # Foo
   > bar baz
   > baz


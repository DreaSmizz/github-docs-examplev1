# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks(`)
- Not to be confused with quotation(')
  
```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Input from the user
num = int(input("Enter a number: "))

if num < 0:
    print("Factorial is not defined for negative numbers.")
elif num == 0:
    print("The factorial of 0 is 1")
else:
    result = factorial(num)
    print(f"The factorial of {num} is {result}")
```
- When you can you should attempt to apply syntax highlighting to your codeblocks

``` Python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Input from the user
num = int(input("Enter a number: "))

if num < 0:
    print("Factorial is not defined for negative numbers.")
elif num == 0:
    print("The factorial of 0 is 1")
else:
    result = factorial(num)
    print(f"The factorial of {num} is {result}")
```

<img width="200px" src="https://github.com/DreaSmizz/github-docs-examplev1/assets/5169195/f3e4de55-0887-4031-8c8d-873676220288" />

Good Cloud Engineers use codeblocks for both Code and Errors that apepar in the console.
> Here is an example of using a codeblock for an error that appears in bash.

```bash
  File "example.py", line 1
    if x > 5
            ^
SyntaxError: invalid syntax
```
## Step 3 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 4 - Use Emoji's (Optional)

Github Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud |`:cloud:`|:cloud:|
| Cloud With Lighting|`:cloud_with_lighting`|🌩️|


## Step 5 - How to create a table

You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud |`:cloud:`|:cloud:|
| Cloud With Lighting|`:cloud_with_lighting`|🌩️|
```
Github extends the functionaility of Markdown tables to provide more alignment and table cell formatting options. [sup>[2]</sup>
](#external-references)


## External References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/). 
- [Basic writing and formatting syntax(Github)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) 
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-)<sup>[2]</sup>
  

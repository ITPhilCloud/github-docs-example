# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (') 

```
# Program to check if a number is prime or not

num = 29

# To take input from the user
#num = int(input("Enter a number: "))

# define a flag variable
flag = False

if num == 1:
    print(num, "is not a prime number")
elif num > 1:
    # check for factors
    for i in range(2, num):
        if (num % i) == 0:
            # if factor is found, set flag to True
            flag = True
            # break out of loop
            break

    # check if flag is True
    if flag:
        print(num, "is not a prime number")
    else:
        print(num, "is a prime number")
```

- When you can you should attempt to apply syntax highlighting to your codeblocks.

```python
# Program to check if a number is prime or not

num = 29

# To take input from the user
#num = int(input("Enter a number: "))

# define a flag variable
flag = False

if num == 1:
    print(num, "is not a prime number")
elif num > 1:
    # check for factors
    for i in range(2, num):
        if (num % i) == 0:
            # if factor is found, set flag to True
            flag = True
            # break out of loop
            break

    # check if flag is True
    if flag:
        print(num, "is not a prime number")
    else:
        print(num, "is a prime number")
```

- Make note of where the backtick button is located.
- It should appear above the tab key,
- but it may vary based on your keyboard layout.

<img width="200px" src="https://github.com/ITPhilCloud/github-docs-example/assets/138229038/a0ca7f66-ed10-49e9-94e0-399daa4087c8"/>

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ZeroDivisionError: division by zero
```

> Here is an example of using a codeblock for an error that appears in bash.


## Step 3 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

- [x] Finish step 1
- [ ] Finish step 2
- [x] Finish step 3

## Step 4 - Use Emojis (Optional)

Github Flavoured Markdown (GFM) supports emoji shortcodes. 
Here are some examples:


| Name  | Shortcode | Emoji |
| --- | --- | --- |
| Cloud  | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` | 🌩️ |

## Step 5 - How to create a table

You can use the following markdown format to creat tables:
```md
| Name  | Shortcode | Emoji |
| --- | --- | --- |
| Cloud  | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` | 🌩️ |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)

## External References

- [Github Markdown - Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) 

- [Python Program to Check Prime Number](https://www.programiz.com/python-programming/examples/prime-number) 

- [typing a backtick on Mac OS X Snow Leopard](https://apple.stackexchange.com/questions/69820/typing-a-backtick-on-mac-os-x-snow-leopard)

- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>

- [GFM - Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
  

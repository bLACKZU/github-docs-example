# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown helps to do a very nice documentation for code and comments associated with it. 

Anything that is needed as a part of your project repo *README*, can be nicely done with the help of codeblocks in **Github Flavoured Markdown**.

A good ***Cloud Engineer*** makes use of **Codeblocks** to document their piece of work.

- In order to create codeblocks you need to use 3 backticks`(```)` that comes with the tilde button in your keyboard.
- Do not confuse this with quotations`('')`


```python
#Solution.py
def add_numbers(a, b):
    return a + b
    
print(add_numbers(5, 3))  # Output: 8
```

- A good ***Cloud Engineer*** not only documents blocks of code but also documents the *errors* that they come across

```bash
Traceback (most recent call last):
  File "Solution.py", line 3, in <module>
    result = numerator / denominator
ZeroDivisionError: division by zero
```

## Step 2 - Todo List 
- [x] Write goooooooooooooood documentation
- [x] Update Github
- [x] Learn in Public

## Step 3 - Tables & Emojis
| Name | Shortcode | Emoji
| --- | --- | --- |
| Cloud | `:cloud:` | ☁️ |
| Smile | `:smile:` | 😄 |
| Office | `:office:` | 🏢 |
| Coffee | `:coffee:` | ☕ | 

## Step 4 - Anchor
[Read this to get a job in Cloud right now!](github-docs-example/random-text/random.md)

## References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)<sup>1</sup>
- [Basic syntax and formatting](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sup>2</sup>
- [Codeblocks](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)<sup>3</sup>
- [Github Markdown Editor & GFM](https://www.youtube.com/watch?v=O9z6OvL-AQQ&list=PLBfufR7vyJJ4q5YCPl4o2XAzGRZUjuD-A&index=16)<sup>4</sup>
- [GFM Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet)<sup>5</sup>

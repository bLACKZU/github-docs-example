# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown helps to do a very nice documentation for code and comments associated with it. 

Anything that is needed as a part of your project repo *README*, can be nicely done with the help of codeblocks in **Github Flavoured Markdown**.

A good ***Cloud Engineer*** makes use of **Codeblocks** to document their piece of work.

- In order to create codeblocks you need to use 3 backticks`(```)` that comes with the tilde button in your keyboard.
- Do not confuse this with quotations`('')`


```python
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
## References
- [Basic syntax and formatting](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sup>1</sup>
- [Codeblocks](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)<sup>2</sup>
- [Github Markdown Editor & GFM](https://www.youtube.com/watch?v=O9z6OvL-AQQ&list=PLBfufR7vyJJ4q5YCPl4o2XAzGRZUjuD-A&index=16)<sup>3</sup>

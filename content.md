If more than a small snippet of code is needed in Markdown, a code block can be used. Code block s are created by wrapping the code in triple backticks (```) or by indenting the code with four spaces.

When using triple backticks, the language of the code can be specified after the opening backticks. This allows for syntax highlighting in many Markdown renderers.

For example, the following code:

````markdown
```python
def hello_world():
    print("Hello, world!")
```
````

will render as:

```python
def hello_world():
    print("Hello, world!")
```

The exact rendering of the code block may vary depending on the Markdown renderer being used. Some renderers may also support additional features, such as line numbers or an embedded copy button.
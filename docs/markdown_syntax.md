# Markdown Syntax

## Links

### Intern
```[Markdown Syntax](/mkdocs/markdown_syntax/)```

[Markdown Syntax](/mkdocs/markdown_syntax/)

### Extern

```[Markdown Syntax](https://links.zur.seite)```

[Markdown Syntax](https://links.zur.seite)

## Code Blocks

- EIn Codeblock wird immer mit ``` eingeleitet und abgeschlossen. Alles was sich innerhalb der 3 Zeichen befindet wird als Codeblock dargestellt
- Dem Codeblock kann man einen Titel übergeben. Beispiel den Datenamen. ``` title="datei.py"
- Auch kann man dem Codeblock übergeben in welcher Programiersprache der Code geschrieben wurde. ```py für Python usw.
- Zeilenummern kann man auch anzeigen: ```linenums="1"

In dem Beispiel unten: ```py title="add_numbers.py" linenums="1"


```py title="add_numbers.py" linenums="1"

# Function to add two numbers
def add_two_numbers(num1, num2):
    return num1 + num2

# Example usage
result = add_two_numbers(5, 3)
print('The sum is:', result)
```
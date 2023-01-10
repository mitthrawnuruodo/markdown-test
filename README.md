# Markdown Test

## Headers

# This is a h1
## This is a h2
### This is a h3
#### This is a h4
##### This is a h5
###### This is a h6

```md
# This is a h1
## This is a h2
### This is a h3
#### This is a h4
##### This is a h5
###### This is a h6
```

## Paragraphs

This is a paragraph

This is anoter paragraph

And yet another paragraph

This paragraph has a linebreak using double spaces  
before continuing on a new line without a blank line

```md
This is a paragraph

This is anoter paragraph

And yet another paragraph

This paragraph has a linebreak using double spaces  
before continuing on a new line without a blank line
```

## Text styling

This is plain text.  
**This is bold text**  
*This text is italicized*  
~~This was mistaken text~~  
**This text is _extremely_ important**  
***All this text is important***  
This is a an example of <sub>subscript text</sub>  
This is a an example of <sup>superscript text</sup>  

Text that is not a quote

> Text that is a quote

```md
This is plain text.  
**This is bold text**  
*This text is italicized*  
~~This was mistaken text~~  
**This text is _extremely_ important**  
***All this text is important***  
This is a an example of <sub>subscript text</sub>  
This is a an example of <sup>superscript text</sup>  

Text that is not a quote

> Text that is a quote
```

## Code

Use `git status` to list all new or modified files that haven't yet been committed.

```md
Use `git status` to list all new or modified files that haven't yet been committed.
```

Some basic Git commands are:

```
git status
git add
git commit
```

````md
Some basic Git commands are:

```
git status
git add
git commit
```
````

Put this in HTML:
```html
<p>This is a HTML tag</p>
```

Then add CSS to add color:
```css
.p { color: green; }
```

And log out to Console using JavaScript:
```js
console.log("Whatever you want");
```

````md
Put this in HTML:
```html
<p>This is a HTML tag</p>
```

Then add CSS to add color:
```css
.p { color: green; }
```

And log out to Console using JavaScript:
```js
console.log("Whatever you want");
```
````

The background color should be `#ffffff` for light mode and `#0d1117` for dark mode. Test: `#0969DA` or `rgb(9, 105, 218)`

> The visualization of the color is only supported in issues, pull requests, and discussions.

## Links

This site was built using [GitHub Pages](https://pages.github.com/).

```md
This site was built using [GitHub Pages](https://pages.github.com/)
```

[Contribution guidelines for this project](docs/CONTRIBUTING.md)

```md
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

<small>Note: The relative link target doesn't exist and will give a 404 error.</small>

## Images

![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

```md
![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)
```

## Unordered list

- George Washington
* John Adams
+ Thomas Jefferson

```md
- George Washington
* John Adams
+ Thomas Jefferson
```

## Ordered list

1. James Madison
1. James Monroe
1. John Quincy Adams

```md
1. James Madison
1. James Monroe
1. John Quincy Adams
```

## Nested list

1. First list item
   - First nested list item
     - Second nested list item
2. Second (main) list item

```md
1. First list item
   - First nested list item
     - Second nested list item
2. Second (main) list item
```

## Task list

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

```md
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
```

## Footnotes

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.

```md
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
```

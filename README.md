# Task2.2_PuigMarti
We can apply a few formats while using a markdown document.
For example: 

# Headers
That go from h1 to h6, we use ``#`` to define them. 

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# *Emphasis*

Which can be used putting the words between two ``*``, can be done with _underscores_ ``_ _`` too. They can be **Combined in _one_ sentence**

# Lists

To make lists we use *, numbers followed by a dot or minuses and pluses `` + - `` 
``` 
1.
2.
3.
```
 to make ordered lists

* First item
* Second item

1. First item
2. second item

# Links

We have two ways of creating a link, using `` [text](link) ``, or just using ``[ ]``
[This is a test link](https://www.google.com)

# Images
We insert images the same way we insert links ``` ![sample text] (link)```

![rektles](https://i.blogs.es/ee4814/rekkles-cry/450_1000.jpg)


# Code and syntax highlighting

This can be done in a few different ways

`Using `` and putting the sentence between it` 
This is used for inline code 

```
We can use 3 back-ticks ` to highlight blocks of code 
```
# Tables


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

They are done with at least 3 dashes between each header cell.
Outer pipes``|`` are optional
Colons are used to align the columns
Inline markdown can be used 

```
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```

# Blockquotes 

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

It's done with ``>`` and its used to make sure long lines of text are properly quoted

# Inline HTML

Raw HTML can be used in the markdowns documents.
But using markdown in the inline HTML won't work well

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

```
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
```

# Horizontal rule 

Use 3 or more 
```

***

---

___
```


***

---

___


# Line breaks


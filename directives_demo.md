# Directives Demo
A list of all directives I could find, translated into MyST.

```
"Just triple back-tics with no directive name creates this Python code box with a copy button."
```

## From Sphinx

### Admonitions

```{admonition} Behold! A generic admonition
admonition
```

```{attention}
attention
```

```{caution}
caution
```

```{danger}
danger
```

```{error}
error
```
```{warning}
warning
```

```{hint}
hint
```

```{tip}
tip
```

```{important}
important
```

```{note}
note
```

### image
```{image} images/cool.jpg

```

### figure 
```{figure} images/cool.jpg

```

### topic
```{topic} Test Topic 

Putting some content here.
```


### sidebar 
```{sidebar} Test Sidebar
Sidebar Content
```


### line block 
Deprecated, and doesn't seem to work.

### parsed literal
```{parsed-literal}
"This is the content of a parsed literal block."
"It appears to be identical to what you get from plain backtics"
```

### code
```{code} python3
def my_function():
  print("testing code block")
  print(2*40)
```
### math
```{math}
\aleph = 2^\aleph
```

### rubric
```{rubric} A Rubric is a Heading 
```

### epigraph
```{epigraph}
I am the sign of the letter and the designation of the division.

-- Thunder, Perfect Mind
```

### highlights
```{highlights}
Highlights include:
* The smog that rubs its back.
* The shadow of this red rock.

Must end with a non-list paragraph element or the attribution won't look cool.

-- The textbook of footnoted poetry 

```

### pull-quote
```{pull-quote}
A beautiful pull-quote that draws the reader in. Looks exactly like highlights and epigraphs though.

-- a brilliant observer
```

### compound paragraph
```{compound}
A compound paragraph is a paragraph with things inside it like:

* lists
* literal blocks
* tables

That are still part of the same paragraph.

```

### container
```{container} special
This content will be in a generic block-level container with the class "special" because that's the argument I passed to the directive.
```

### Tables
* Restructured Text supports 3 kinds of tables.
* I can't get them to work.
* They are table, csv-table, and list table.





### contents
```{contents} Test Table of Contents
:depth: 3
```

### include 

### toctree 
Hiding
```{toctree}
:maxdepth: 2
widgets_demo
```


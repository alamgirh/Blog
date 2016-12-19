---
layout: post
date: 2016-10-10
author: Alamgir Hossain
title: Markdown Tutorial
categories: tutorial
tags: Markdown Tutorial
---

### Headings

# Headings 1
## Headings 2
### Headings 3
#### Headings 4
#### Headings 5
##### Headings 6

#### Code

```markdown
# Headings 1
## Headings 2
### Headings 3
#### Headings 4
#### Headings 5
##### Headings 6
```

### Headings (alternative way)

Headings 1
======

Headings 2
------

#### Code 

```markdown
Headings 1
======

Headings 2
------
```

### Links

[Jupyter Notebook](http://jupyter.org/)

[Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

#### Code

```markdown
[Jupyter Notebook](http://jupyter.org/)
[Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
```

### Bullet Points

- $d = b^2-4ac$; (<u>comment about roots</u>) 
 - $d \ge 0$; roots are **real** ~~not only positive~~
    - $d > 0$; roots are real and *distinct*
    - $d = 0$; roots are real and _same_
 - $d<0$; roots are __complex__
 
#### Code

```markdown
- $d = b^2-4ac$;  (<u>comment about roots</u>)
 - $d \ge 0$;  roots are **real** ~~not only positive~~
    - $d > 0$; roots are real and *distinct*
    - $d = 0$; roots are real and _same_
 - $d<0$; roots are __complex__
```

### Bullet Points (numeric)

$d = b^2-4ac$;  (comment about roots)

1. $d \ge 0$;  roots are real
   1. $d > 0$; roots are real and distinct
   2. $d = 0$; roots are real and same
2. $d<0$; roots are complex
 
#### Code
 
```markdown
$d = b^2-4ac$;  (comment about roots)
1. $d \ge 0$;  roots are real
   1. $d > 0$; roots are real and distinct
   2. $d = 0$; roots are real and same
2. $d<0$; roots are complex
```

### Table

| d = b^2-4ac    | d = b^2-4ac     | d = b^2-4ac   | comment about roots         |
|:---------------|:---------------:|--------------:|-----------------------------|
| d>0            | d>0             | d>0           | roots are real and distinct |
| d = 0          | d = 0           | d = 0         | roots are real and same     |

#### Code 

```markdown
| d = b^2-4ac    | d = b^2-4ac     | d = b^2-4ac   | comment about roots         |
|:---------------|:---------------:|--------------:|-----------------------------|
| d>0            | d>0             | d>0           | roots are real and distinct |
| d = 0          | d = 0           | d = 0         | roots are real and same     |  
```

### Figure

If we have a figure and the file name is quadraticplots.png then the markdown code for showing this figure is

![LaTex: Quadratic Functions](../figure/quadraticplots.png)

#### Code (Markdown)

```markdown
![LaTex: Quadratic Functions](figure/quadraticplots.png)
```

### Showing Code

```python
def vertex(a,b,c):
   x0 = -b/(2.0*a)
   y0 = c-b*b/(4.0*a)
   return [x0, y0];
```

#### Code

```markdown
```python
def vertex(a,b,c):
   x0 = -b/(2.0*a)
   y0 = c-b*b/(4.0*a)
   return [x0, y0];
   ```
``` 

### Horizontal Rule

three or more Hyphens, Asterisks or Underscores e.g.

roots are real and distinct 
---

roots are real and same
***

roots are complex
___

```markdown
roots are real and distinct 
---

roots are real and same
***

roots are complex
___
```


### Quotes

> Don't be afraid to work, don't be afraid to try,
> don't be afraid to network, and don't be shy!

Another example
> Hope is a good thing, maybe the best of things, and no good thing ever dies. -Andy Dufresne (The Shawshank Redemption)

#### Code

```markdown
> Don't be afraid to work, don't be afraid to try,
> don't be afraid to network, and don't be shy!

Another example

> Hope is a good thing, maybe the best of things, and no good thing ever dies. -Andy Dufresne (The Shawshank Redemption)
```

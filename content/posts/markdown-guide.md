+++
title = 'Markdown Guide'
date = 2024-03-23T19:46:32+05:30
draft = false
showTableOfContents = true
description = "A simple and fast Markdown Guide"
type = "post"
tags = ["blog", "markdown", "simple"]
+++

This is a simple and fast paced, on point use of markdown and its syntax.

You can use `html` in markdown but it is recomended not to do so.

## Headings

These are headings. Do not use them for a smaller font size.

```md
# H1

## H2

### H3

#### H4

##### H5

###### H6

```

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Paragraph

Anything that is not a special element is a paragraph. It is written without any special formatting.

## Basic formatting.

This is normal formatting.
```md
*italics*
**bold**
***bold and italics***
[Link Text](link)
```
*italics*
**bold**
***bold and italics***
[Link Text](https://example.com/)

## Blockquotes

```md
> This is a blockquote.
```

> This is a blockquote.

## Tables

```md
| Hello | World |
| ----- | ----- |
| This is me | This is also me |
```

| Hello | World |
| ----- | ----- |
| This is me | This is also me |

## Code Blocks

Code is written withing three back ticks "```".

```c
#include <stdio.h>

int main(int argc, char* argv[]) {
	printf("Hello World");
}
````

## Lists

### Ordered

```md
1. code
2. forces
```
1. code
2. forces

### Un-Ordered

```md
- Hello
- World
	- Nested Hello
	- Nested world
```
- Hello
- World
	- Nested Hello
	- Nested world
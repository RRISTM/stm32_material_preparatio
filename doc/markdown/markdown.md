# Markdown

Markdown is a way to style text on the web. 
Where the formating is done automatically. 

[Link](https://guides.github.com/features/mastering-markdown/)

## Basic markdown formating syntax

1. Headers

```
# This is an `<h1>` tag
## This is an `<h2>` tag
###### This is an `<h6>` tag
```

It will be renedered like this:

---

# This is an `<h1>` tag
## This is an `<h2>` tag
###### This is an `<h6>` tag

---

2. Emphasis

```
*This text will be italic*
_This will also be italic_
**This text will be bold**
__This will also be bold__
_You **can** combine them_
```

---

*This text will be italic*

_This will also be italic_

**This text will be bold**

__This will also be bold__

_You **can** combine them_

---

3. Lists

 1.  Unordered
   
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

---
* Item 1
* Item 2
  * Item 2a
  * Item 2b
---
 
 1. Ordered

```
1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b

```

---
1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b
---

4. Images

```
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
```

5. Links
   
```
[GitHub](http://github.com)
```

6. Inline code
   
```
I think you should use an
`<addr>` element here instead.
```

I think you should use an
`<addr>` element here instead.

7. Syntax higlitining

\```c

while(1){

    uint32_t i++;

}

\```

will render like

```c
while(1){
    uint32_t i++;
}
```

Currently is supportedis `c` on request we can add more syntaxes. 

Languages must be suported by [react-syntax-highlighter](https://github.com/react-syntax-highlighter/react-syntax-highlighter)


## How to write md

The markdown parser [markdown-to-jsx](https://github.com/probablyup/markdown-to-jsx) have some specific formating needs. 

Mainly between specific element is good to make a ne line between elements (2x ENTER). If not it will be as one line. 

```
Test text [link](www.google.com) line.

Test with enter

[link](www.google.com)

continue 
```

---

Test text 
[link](www.google.com) 
line.

Test with enter

[link](www.google.com)

continue 

---

Horizontal line

`---`

---


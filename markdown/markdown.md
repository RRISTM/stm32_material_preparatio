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
![GitHub Logo](/img/logo.png)
Format: ![Alt Text](url)
```

Please you must create img folder in place where is relevant *.md file

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

### Out modification

If you dont want not to have **copy** button
Use suffix `-nc` (not copy) together with language `c-nc`

\```c-nc   

\```

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



# Additional updates

You can wrap thext into colored box with 

```md
<awarning>
Orange warning box
</awarning>
```

It will looks like:

<awarning>
Orange warning box
</awarning>

```md
<asuccess>
Green success box
</asuccess>
```

It will looks like:

<asuccess>
Green success box
</asuccess>

```md
<ainfo>
Blue info box
</ainfo>
```

It will looks like:

<ainfo>
Blue info box
</ainfo>

```md
<aerror>
Red error box
</aerror>
```

It will looks like:

<aerror>
Red error box
</aerror>




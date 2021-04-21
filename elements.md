---
layout: default
title: "All Elements"
---

---
# Headers Example

These are header examples

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

---
# Lists

Bulleted List

- first
- second
- third 
- fourth

Numbered List

1. first
2. second
3. third 
4. fourth

Nested List

1. First item.
   - Item 1
   - Item 2
   - Item 3
1. Second item.
   - Nested item 1
   - Nested item 2
   - Nested item 3

---
# Blockquotes

> Darkness cannot drive out darkness: only light can do that. Hate cannot drive out hate: only love can do that. - **Martin Luther King Jr.**

Nested blockquotes

> I find it hard to believe.
> > That everything you see is different from the things that you've been told.

---
# Code snippet

This is an example of a C# code snippet

```csharp
public class HelloWorld()
{
    public void Shout()
    {
        Console.Writeline("Hello World.");
    }
}
```

This is an example javascript code snippet

```javascript
function test() {
    console.log("look ma’, no spaces");
}
```
---
# Tables

First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2

---
# Text

- This is a **bold** text. 
- This is an *italic* text. 
- This is `inline` code.
- This is a ~~strikethrough~~ text.

---
# Link

This is a link to [Google](www.google.com)

---
# Tasks

- [ ] A  
- [ ] B  
- [ ] C  
- [x] A  
- [x] B  
- [x] C  

---
# Math Blocks

$$
\begin{aligned}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{aligned}
$$
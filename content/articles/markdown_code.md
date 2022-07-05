+++
title = "Markdown code"
+++

#### This is my markdown cheatsheet.
```markdown
<!--Headings-->
# Heading 1
## Heading 2
### Heading 3


<!--Italics-->
*This is a italic text*

_This is also a italic text_


<!-- Bold -->
**This is a bold text**
<!-- We can escape astricks by using backslash '\' -->
\*\*This is not a bold text as I have used backslash\*\* <!-- I haven't used one \ because if I do so it will take one backslash and make it italic -->

__This is also a bold text__


<!-- Strikethrough -->
~~This a a strikethrough~~ <!--(Use double ~~ at the end and stating) -->


<!-- Horizontal Rule -->
Use:
*** 
or 
___
or 
---


<!-- Blockquotes -->
> This is a blockquote


<!-- Links -->
[Text](https://botpsycho.netlify.com)
<!-- In the below code if I hover over it, it will show This is my website -->
[Text](https://botpsycho.netlify.com "This is my website")  


<!-- Unordered lists -->
* Item 1
* Item 2
* Item 3
    * Nested item 1 <!-- Use tabs -->
      * Nested item 2
        * Nested item 3
          * And so on 


 <!--Ordered lists  -->

 1. Item 1
 2. Itwm 2
 3. Item 3


<!-- Inline code block -->
<!-- Use ` at the end and starting of the block -->
`<p>This is a inline code block</p>`


<!-- Image -->
<!-- Same as links, just as ! in front of it -->
![Markdown Logo](https://markdown-here.com/img/icon256.png)'




---

## Github mardown

<!-- Code blocks -->

<!-- Use ``` then the name of syntax, in this case its bash and then ``` -->
```bash
mkdir ~/.local/bin
git clone https://github.com/botpsycho/scripts ~/.local/bin
rm -rf ~/.local/bin/.git
```

<!-- Tables -->
|Name| Email      |
|----|------------|
|abc | abc@abc.com|
|bcd | bcd@bcd.com|
|efg | efg@efg.com|
|----|------------|

<!-- Task lists -->
* [x] Task 1
* [x] Task 2
* [ ] Task 3 

```

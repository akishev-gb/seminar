# **Markdown Cheatsheet**

## **Table of contents**

1. [Headers](#Headers)
2. [Emphasis](#Emphasis)
3. [Lists](#Lists)
4. [Links](#Links)
5. [Images](#Images)

<div id='Headers'/>

## **Headers**
To make a header you shoud use: "#". The more "#" you use, the lower the text is.<br>
For example:

# H1 title
## H2 title
### H3 title
Alternative H1 title
===
Alternative H2 title 
---

<div id='Emphasis'/>

## **Emphasis**
To make a curve text you shoud use "* *" or "_ _"around the word or text.<br>
For example: *This is a curve text.*

To make a fat text you shoud use "** **" or "__ __"around the word or text.<br>
For example: **This is a fat text.**

To make a curve and fat text you shoud use "*** ***" around the word or text.<br>
For example: ***This is a curve and fat text.***

To make a scratch text you shoud use "~~~~" around the word or text.<br>
For example: ~~This is a scratched text.~~

<div id='Lists'/>

## **Lists**
To make a list you can simply use "*", "+" or "-".<br>
For example:
* First element
- Second element
+ Third element

You can also use numbers.<br>
For example:
1. First element
2. Second element
3. Third element

You can also add text ander list by using spacebar 3 times.<br>
For example:
1. This is first element
   
   And this is text undernith it. Use it like like you want
2. This is third element

   And once again, feel free to write whatever you want.

You can make complex lists. Just use spacebar. And remember: list is numbered automatically.<br>
For example:
1. First element
   1. First sub-element
   1. Second sub-element
1. Second Element
   1. First sub-element
      * First element
        - Just
        + Stop
      * Second elemnt
    1. Second sub-elements.
        1. This is
        1. Getting
        1. Complex

<div id='Links'/>

## **Links**
The common way to create a link is to use a construction like: [text"]"(link) or [text"]"(link "promt") without "".<br>
For example: [Google](https://google.com "Main google page")

You can create links to other documents, if you write their pathway in().<br>
For example:
Tap [here](..\gitSeminarDz1\Test.md) to go to another file.

You can use reference style links using[a]. And after you should write [a]: link.<br>
For example: [Yandex][1].

[1]: https://yandex.by/

<div id='Images'/>

## **Images**

To insert an image you have to use link to it, like in **link** part.

[Markdown logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png "Markdow logo in browser")

To insert a whole image you should simply put ! befor [].

![Markdown logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png "Markdow logo in browser")

---

---

# Part II


## **Table of content**
1. [Sheets](#Sheets)
2. [Quoting](#Quoting)
3. [Footnotes](#Footnotes)
4. [Videos](#Videos)

<div id='Sheets'/>

## Sheets

To make a sheet just use "|" To adjust it use ":".<br>
For example:

|column1|column2|column3|
|:------|:-----:|------:|
|smth   |smth   |smth   |
|smth   |smth   |smth   |

<div id='Quoting'/>

## Quoting

To create a quote you simly need to use ">"<br>
For example:

This is not a quote.<br>
>But this is.

>This is
>another way
>to create a qute.
>Every line use 
>this ">" symbol.

Also you can create a levels of quoting.<br>
For example:

>This is level 1 quote.
>>This is level 2 quote.
>>>This is level 3 quote.


<div id='Footnotes'/>

## Footnotes

Creating footnotes is similar to creating links. You should use [].<br>
For example:

This is[^1] a footnote.

And [^note] this is also a footnote.

[^1]: this is a footnote.

[^note]: and this is a
  footnote too.

```cpp
   if(a > b)
   {
      a = a + 1;
   }
```

<div id='Videos'/>

## Videos

To insert a video you can use a following construction:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=pTCROLZLhDM
" target="_blank"><img src="http://img.youtube.com/vi/pTCROLZLhDM/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

## Text for push

## Text for pull

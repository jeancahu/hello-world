<!--Comment this way-->
<!--Define titles & subtitles with an amount of #'s-->
<!-- Title -->
# Hello world
A newbie's first markdown readme <!--Simple Text-->



<!--Headings/Subtitles -->
## Markdown Basics
---
Part where I'm learning the markdown basics.

.

### Headings/Subtitles:
Use a different amount of #'s.

.
### Block Text:
Press tab to define the indentation.
<!--Press tab to make block text-->

         Block text 
         still block comment

.


### Italics:
Enclose between asterisks (\*text\*) or between underscores (\_text\_).

.

### Strong Text:
Enclose between two pairs of asterisks (\*\*text\*\*) or between two pairs of underscores (\_\_text\_\_).

.


### Strikethrough:
Enclose between two pairs of tildes (\~\~text\~\~).

.
### Horizontal Rule:
Use triple underscores (\_\_\_) or triple hyphen (\-\-\-).

.

### Blockquote:
Use the greater than symbol (\>) before the text.

.
### Links:
Enclose the description text of the link between brackets (\[\]) and next to it, the url between parenthesis (\(\)).

To add an url title, put the title enclosed by quotes marks (\(Url\) \"Url Title\").

.

### Unordered List:
Use an asterisk (\*) for each item. To do **nested items** use tab and then use the asterisk.

.

### Ordered List:
Put 1\. before each element of the list.

.

### Inline Code Block:
Enclose the code between two acutes/backquotes (\`).

.

### Images:
Put an exclamation symbol (\!), enclose the description text of the image between brackets (\[\]) and next to it, the url of the image between parenthesis (\(\)).

.

---
___


## Testing
---
The segment where tests of what has been learned are carried out.

.

### Heading Testing:
<!--begin Headings Testing-->
#### Heading with 4 #'s
##### Heading with 5 #'s
###### Heading with 6 #'s
####### Heading with 7 #'s
<!--end Headings Testing-->
.
<!--begin Block text Testing-->
### Block Text Texting:

no tab

    1 tab
        2 tab
            3 tab
                4 tab
<!--end Block text Testing-->

.

<!--begin Italics Testing-->
### Italics:
(\*text\*) = *text in italic between asterisks*

(\_text\_) = _text in italic between underscores_
<!--end Italics Testing-->

.

<!--begin Strong Text Testing-->
### Strong:
(\*\*text\*\*) = **Strong text between two asterisks**

(\_\_text\_\_) = __Strong text between two underscores__
<!--end Strong Text Testing-->

.


<!--begin Strikethrough Testing-->
### Strikethrough:
(\~\~text\~\~) = ~~Strikethrough text between a pair of tildes~~
<!--end Strikethrough Testing-->

.

<!--begin Horizontal Rule Testing-->
### Horizontal Rule:
(\-\-\-) = 

---
(\_\_\_) =

___
.

<!--end Horizontal Rule Testing-->

<!--begin Blockquote Testing-->
### Blockquote:
(\>This is a quote.)=
> This is a quote. 
<!--end Blockquote Testing-->

.

<!--begin Links Testing-->
### Links:
\[Link Descrption\] \(URL\) without url title=
[Joji - Tick Tock](https://www.youtube.com/watch?v=2FCo7OxVoeY&list=PLzjD-HnzMfXLVK_7xjVvu6MY590ioHqyS&index=3&ab_channel=Joji)

\[Link Descrption\] \(URL\) with url title=
[Joji - Tick Tock](https://www.youtube.com/watch?v=2FCo7OxVoeY&list=PLzjD-HnzMfXLVK_7xjVvu6MY590ioHqyS&index=3&ab_channel=Joji "Joji - Tick Tock")

*Put the cursor over the url's.
<!--end Links Testing-->

.

<!--begin Unordered List Testing-->
### Unordered List:
\* Item=
 * Item

    * tab + \* Nested Item 1
        * tab + tab + \* Nested Item 2
            * tab + tab + tab + \* Nested Item 3

\* Second Item=
* Second Item

\* Third Item =
* Third Item

<!--end Unordered List Testing-->

.

<!--begin Ordered List Testing-->
### Ordered List:
(1\. First ordered item

1\. Second ordered item

1\. Third ordered item)=

1. First ordered item

1. Second ordered item

1. Third ordered item
<!--end Ordered List Testing-->

.

<!--begin Inline Code Block Testing-->
### Inline Code Block:
\` <\p>This is code.<\/p>\` =

`<p> This is code </p>`
<!--end Inline Code Block Testing-->

.

<!--begin Images Testing-->
### Images:
\!\[My avatar pic\]\(https://avatars2.githubusercontent.com/u/16785324?s=460&v=4\) =

![My avatar pic](https://avatars2.githubusercontent.com/u/16785324?s=460&v=4)
<!--end Images Testing-->

.

---
___


## Github Flavored Markdown
---

The segment of github's markdown syntax.
=

<!--begin Code Blocks Github-->
### Code Blocks:

Use triple acutes/backquotes (\`) in the lines before and after the code. Specify the syntax after the first backquotes in the same line.

\`\`\`bash

npm install

npm start

\`\`\`

=
```bash
npm install
npm start
```

\`\`\`javascript

function add(num1, num2){

return num1 + num2;

}

\`\`\`

=

```javascript
    function add(num1, num2) {
     return num1 + num2;
     }
```

Test without specyfing the syntax: 

\`\`\`

function add(num1, num2){

return num1 + num2;

}

\`\`\`

=

```
    function add(num1, num2) {
        return num1 + num2;
        }
```


\`\`\`python

def add(num1, num2):

return num1 + num2

\`\`\`

=

```python
    def add(num1, num2):
     return num1 + num2
```
<!--end Code Blocks Github-->
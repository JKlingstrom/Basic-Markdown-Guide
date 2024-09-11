# Basic Markdown Guide
This is a basic guide to get you started with markdown, but there's a lot more that can be done! <br>
I also added a cheat-sheet [here](https://github.com/JKlingstrom/Basic-Markdown-Guide/blob/main/Markdown Cheat-Sheet.pdf)

## Table-of-Contents

- [Headers](#Headers)
- [Formatting](#Formatting)
	- [Breaks](#Breaks)
- [Blocks](#Blocks)
- [Lists](#Lists)
	- [Unordered-Lists](#Unordered-Lists)
- [Links](#Links)
	- [ToC](#ToC) = ``[ToC](#ToC)``
- [Tasks](#Tasks)
- [Tables](#Tables)
- [Code](#Code)
***
## Getting Started !

On your GitHub profile, if it’s not already created, create a `README.md` file. This special file will appear on the home page of your account. You can find it at:  
`https://github.com/yourusername`

The GitHub markdown editor has both an edit and a preview mode, making it a good place to start writing markdown. There are also several other editors that support markdown. Here are a few examples:

- [Obsidian](https://obsidian.md/)
- [PyCharm](https://www.jetbrains.com/pycharm/)
- [Visual Studio Code](https://code.visualstudio.com/)



The great thing about these editors is that you can have both an edit and preview window open simultaneously, allowing you to see changes as you write.
>Personally, I use obsidian since I also use markdown for my notes.

***
## Headers!

To start adding titles or headers, use a hashtag `#`. One hashtag creates the largest header size, and using up to six hashtags creates progressively smaller header sizes, like this: <br>



```
# Header 1
```
⬇
# Header 1 
```
## Header 2
```
⬇
## Header 2
```
# Header 3
``` 
⬇
### Header 3
```
# Header 4
``` 
⬇
#### Header 4
```
# Header 5
``` 
⬇
##### Header 5
```
# Header 6
``` 
⬇
###### Header 6
<br>

> Notice that there is a space between the `#` and `header x`.

<br>

[TOP](#Table-of-Contents)
***
## Formatting 
Formatting text with markdown is very easy. Here's how to do some of the basics!
To make text **bold**, two asterisks `**` is placed before and after the word or text you want bold. <br>
`**bold**` ➡ **bold** <br>
<br>
To make text _italic_, place one underscore `_` before and after the word or text you want italicize. <br>
`_italic_` ➡ _italic_ <br>
<br>
To make text both bold and italic, use a combination of the methods mentioned above.
`**_Bold and italic_**` ➡ **_Bold and italic_** <br>

We can also mix the asterisks `*` and underscores `_` like this:
`__*works the same*__` ➡  __*works the same*__ <br>

To highlight text, place two equal signs `==` before and after the word or text you want to highlight. <br>
`==highlighted==` ➡ ==highlighted== <br>

>Highlighting doesn't work like this on GitHub, but it does in many other markdown editors, so I thought I would mention it. <br>

To make text strikethrough, use two tildes `~~` before and after the word or text you want to strikethrough. <br>
`~~strikethrough~~`  ➡ ~~strikethrough~~ <br>
<br>

## Breaks

Sometimes you need more space between different pieces of text.

You can use a single Enter key stroke to add a new line, but you can't add more than one blank line this way. This is where `<br>` tags come in.


Test text:

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt **explicabo**.

Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
***


>As we can see, the text is separated after the word **`explicabo.`** by just pressing the Enter key. However, if we want even more space between the two pieces of text, pressing Enter multiple times will not work.

***
By adding the `<br>` tag to the same text, like this:

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

`<br>`

Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
***

⬇ We get the following output:
***
Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

<br>

Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
>Here we can see that the space between the two text's have increased and we can add how many `<br>` tags as we want.





<br><br>
[TOP](#Table-of-Contents)
***
## Blocks


To make a blockquote, use the greater-than symbol `>` in front of the text you want to quote. <br>  
`> This text is in a blockquote` 
⬇

> This text is in a blockquote

<br><br>
To include larger chunks of text, use three backticks (```) above and below the block of text you want to format. <br>

<br>

\`\`\`

This will take all the text and make it a block, and make it easy to copy!

\`\`\`


⬇

```
This will take all the text and make it a block, and make it easy to copy!
```
>Note that the three backticks (```)  should be placed above and below the block of text you want to format.



<br><br>
[TOP](#Table-of-Contents)
***
## Lists
Another very useful feature is creating lists! To make a numbered list, simply type: <br> `1. item here` and press Enter. The list will continue automatically.

`1. Item number 1` 

⬇
1. Item number 1
2. Item number 2
3. Item number 3
4. and so on...


We can also create nested lists by starting as we did before and then adding a tab like this: <br>

```
1. Item number 1
2. Item number 2
3. Item number 3
	1. Item A
	2. Item B
		1. Item C
		2. Item D

```

⬇
1. Item number 1
2. Item number 2
3. Item number 3
	1. Item A
	2. Item B
		1. Item C
		2. Item D


## Unordered-Lists

We can also create unordered lists using either the `+` or `-` sign. Both symbols are interchangeable, so you can use whichever you prefer.

```
+ Item 1
- Item 2
+ Item 3
	+ Item A
	+ Item B
	+ Item C
```
⬇
+ Item 1
+ Item 2
+ Item 3
	+ Item A
	+ Item B
	+ Item C


## Tasks
To create a task list, use `- [ ] Task 1:` like this:
```
- [ ] Task 1 
- [ ] Task 2
- [x] Task 3
``` 

⬇
- [ ] Task 1 
- [ ] Task 2
- [x] Task 3


>One thing to note is that you should use `- [ ] Task 1` with spaces around the brackets to ensure proper formatting. In some markdown editors, you can click on these tasks to mark them as complete or incomplete. <br>

[TOP](#Table-of-Contents)
***
## Links
Links can be used for webpages or for navigating within the document, and they are fairly straightforward. Inside the brackets `[ ]`, type the name of the link. Inside the parentheses `( )`, type the actual URL of the website you want to link to.

Example:  
`[Google](https://www.google.com)`

⬇

[Google](https://www.google.com)

Another way to include addresses is to write them directly like this: 

```
https://google.com
```

⬇

https://google.com  
<br>  
Links can also be used in a document, such as in a Table of Contents. The format is similar, but you specify the header instead.

```
[TOP](#Table-of-Contents)
```

⬇

[TOP](#Table-of-Contents)

> This link will take you to the start of the guide.  
> As mentioned above, in the `[ ]` is the name of the link, and in the `( )` is the actual link.

To return from the Table-of-Contents back here, use the link to this header below:

`## ToC`

⬇

## ToC

By adding the following link to the Table-of-Contents, you can jump right back here:

`[ToC](#ToC)`

> [TOP](#Table-of-Contents)  
> This link will take you to the top of the document, to the `#Table-of-Contents` header. From there, you can click the `ToC` link to return here!

> Summary:
> 
> 1. Add a header: `# Test`
> 2. Add a link in the Table-of-Contents: `[Test](#Test)` This will make you jump to the `# Test` header in your document. Also, ensure you **don't** use special characters in header titles (e.g., `Test!`); the `!` will break the link. Additionally, note that in `[Test](#Test)` there is no space between `#` and `Test`, but when creating the header, a space is required. The header you want to go to **can't** have spaces in them, so instead of spaces use `-`




<br><br><br>
[TOP](#Table-of-Contents)
***
## Tables

Tables can be useful but a bit finicky to create by hand. However, I'll show you how to make basic ones.
<br>


```
|Title 1|Title 2|Title 3|
|---|---|---|
|Info 1|Info 2|Info 3|
|Data 1|Data 1|Data 1|
```

⬇

|Title 1|Title 2|Title 3|
|---|---|---|
|Info 1|Info 2|Info 3|
|Data 1|Data 1|Data 1|

You can also align the text within the cells by adding colons. Use `:` to align left, right, or center within the `|`. There should be at least `---` three hyphens for each column. 


```
|Title 1|Title 2|Title 3|
|:---|---:|:---:|
|Info 1|Info 2|Info 3|
|Data 1|Data 1|Data 1|
```

⬇

|Title 1|Title 2|Title 3|
|:---|---:|:---:|
|Info 1|Info 2|Info 3|
|Data 1|Data 1|Data 1|


Here we can see the output from above. By changing the location of the colon `:`, you can adjust the text alignment in the cells.

> One thing to note is that the `|` characters don’t have to align perfectly across rows.

```
|Title 1|Title 2|Title 3|
|:---|-----------:|:------------------:|
|Info 1|Info 2|Info 3     |
|Data 1|Data 1|Data 1     |
```

This will still give the same output: ⬇

|Title 1|Title 2|Title 3|
|:---|-----------:|:------------------:|
|Info 1|Info 2|Info 3     |
|Data 1|Data 1|Data 1     |

[TOP](#Table-of-Contents)
***
## Code

Markdown is very useful for sharing code online and makes it easy to copy!

Here, we use Python as an example, but Markdown works with many other programming languages as well.



\`\`\`python                     
print("Hello World")<br>
\`\`\`
 
 ⬇
 
 

```python 
print("Hello World!")
```


This will enable syntax highlighting for the specified programming language, making the code much easier to read and copy.

>Note that there is no space between the three backticks(\`\`\`) and the program you want the syntax for.
>
>Like this:<br>
> \`\`\`python<br>\`\`\`




<br><br>
[TOP](#Table-of-Contents)
***
## Thanks!

This was a very basic guide to Markdown, and there's a lot more that can be done! I'm still learning but wanted to share the basics to hopefully help others get started!

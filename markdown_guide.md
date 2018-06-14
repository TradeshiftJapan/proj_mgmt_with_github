# Markdown Guide

## Line break

```
line1 (followed by 2 spaces)

line2
<br>
<br>
line3
```

line1 (followed by 2 spaces)

line2
<br>
<br>
line3



## Code

### Code block

> \```<br>
your<br>
code<br>
block<br>
\```


```
your
code
block
```


### Inline code

> your \`code\` block

your `code` block



## Headers

```
# Header 1
## Header 2
### Header 3
...
###### Header 6
```

# Header 1
## Header 2
### Header 3
...
###### Header 6



## Emphasis

Surrounded by _Single underscore_ or *Single asterisk* is Italic.

Surrounded by __Double Underscores__ or **Double asterisks** is Bold.



## Strikethrough

Surrounded by ~~Double tilda~~ is strikethrough.



## Details - Folding

```
<details><summary>Details summary</summary>
Details is descibed in details tag.</details>
```

<details><summary>Details summary</summary>
Details is descibed in details tag.</details>



## List

### Disc type

```
* item 1
* item 2
* item 3
```

* item 1
* item 2
* item 3

```
+ item 1
+ item 2
+ item 3
```

+ item 1
+ item 2
+ item 3

```
- item 1
- item 2
- item 3
```

- item 1
- item 2
- item 3



### Decimal type

```
1. item 1
1. item 2
1. item 3
```

1. item 1
1. item 2
1. item 3

```
1. item 1
  1. item 1 - 1
2. item 2
  1. item 2 - 1
  1. item 2 - 2
3. item 3
```

1. item 1
  1. item 1 - 1
2. item 2
  1. item 2 - 1
  1. item 2 - 2
3. item 3


```
1. item 1
  - item 1 - 1
2. item 2
  - item 2 - 1
  - item 2 - 2
3. Item 3
```

1. item 1
  - item 1 - 1
2. item 2
  - item 2 - 1
  - item 2 - 2
3. Item 3

### Definition type

```
<dl>
  <dt>Apple</dt>
  <dd>Red fruit</dd>
  <dt>Banana</dt>
  <dd>Yellow fruit</dd>
</dl>
```

<dl>
  <dt>Apple</dt>
  <dd>Red fruit</dd>
  <dt>Banana</dt>
  <dd>Yellow fruit</dd>
</dl>



## Checkbox

```
- [ ] Task 1
- [x] Task 2
```

- [ ] Task 1
- [x] Task 2




## Blockquotes

```
> This<br>
is<br>
blockquotes
```
> This<br>
is<br>
blockquotes

```
> This
>> is
>>> blockquotes
```

> This
>> is
>>> blockquotes



## Horizontal ruler

```
* * *
***
*****
- - -
```

* * *
***
*****
- - -




## Links

```
[Link text](http://github.com)
```

[Link text](http://github.com)

```
[this][link-1] is [that][link-1].<br>
[link-1][] is same.
[link-1]:http://github.com
```
[this][link-1] is [that][link-1].<br>
[link-1][] is same.
[link-1]:http://github.com



## Images

```
![Alternate text](http://tsubakicraft.jp/images/hibiki_std.png)
```
![Alternate text](http://tsubakicraft.jp/images/hibiki_std.png)



## Table

```
|Left align|Center align|Right align|
|:-|:-:|-:|
|1|2|3|
|4|5|6|
```

|Left align|Center align|Right align|
|:-|:-:|-:|
|1|2|3|
|4|5|6|



## Text color

```
<font color="Red">Red</font><br>
<font color="#3e3e3e">#3e3e3e</font>
```

<font color="Red">Red</font><br>
<font color="#3e3e3e">#3e3e3e</font>



*Does not work with GitHub*


## Foot Note

Text[1]

[1]: Note

*Does not work with GitHub*

## Escape Markdown

```
> Blockquotes

\> Blockquotes
```

> Blockquotes

\> Blockquotes

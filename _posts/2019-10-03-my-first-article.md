---
title: "我的第一篇文章"
sub_title: "副标题，两边是英文引号"
excerpt: "摘要，这些引号都可以不打"
categories:
  - Markup
elements:
  - content
  - formatting
  - html
  - markup
---

A variety of common HTML elements to demonstrate the theme's stylesheet and verify they have been styled appropriately.

标题：

# Header one

## Header two

### Header three

#### Header four

##### Header five

###### Header six

## 图片：

![](/assets/images/demo.jpg)

## Blockquotes 引用段落

一行：

> Stay hungry. Stay foolish.

多行：

> People think focus means saying yes to the thing you've got to focus on. But that's not what it means at all. It means saying no to the hundred other good ideas that there are. You have to pick carefully. I'm actually as proud of the things we haven't done as the things I have done. Innovation is saying no to 1,000 things.
>
> <footer><strong>Steeve Jobs</strong> &mdash; Apple Worldwide Developers' Conference, 1997</footer>


## Tables

| Employee         | Salary |                                                              |
|------------------|--------|--------------------------------------------------------------|
| [John Doe](#)    | $1     | Because that's all Steve Jobs needed for a salary.           |
| [Jane Doe](#)    | $100K  | For all the blogging she does.                               |
| [Fred Bloggs](#) | $100M  | Pictures are worth a thousand words, right? So Jane × 1,000. |
| [Jane Bloggs](#) | $100B  | With hair like that?! Enough said.                           |

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|-----------------------------|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=============================|
| Foot1   | Foot2   | Foot3   |


## 列表（不带编号）

  * List item one 
      * List item one 
          * List item one
          * List item two
          * List item three
          * List item four
      * List item two
      * List item three
      * List item four
  * List item two
  * List item three
  * List item four

## 列表（带编号）

  1. List item one 
      1. List item one 
          1. List item one
          2. List item two
          3. List item three
          4. List item four
      2. List item two
      3. List item three
      4. List item four
  2. List item two
  3. List item three
  4. List item four

## 按钮

Make any link standout more when applying the `.btn` class.

[Default Button](https://www.google.com){: .btn}
[Primary Button](https://www.google.com){: .btn .btn--primary}
[Accent Button](https://www.google.com){: .btn .btn--accent}
[Success Button](https://www.google.com){: .btn .btn--success}
[Warning Button](https://www.google.com){: .btn .btn--warning}
[Danger Button](https://www.google.com){: .btn .btn--danger}
[Info Button](https://www.google.com){: .btn .btn--info}
[Inverse Button](https://www.google.com){: .btn .btn--inverse}
[Light Outline Button](https://www.google.com){: .btn .btn--light-outline}

```markdown
[Default Button Text](#link){: .btn}
[Primary Button Text](#link){: .btn .btn--primary}
[Accent Button Text](#link){: .btn .btn--accent}
[Success Button Text](#link){: .btn .btn--success}
[Warning Button Text](#link){: .btn .btn--warning}
[Danger Button Text](#link){: .btn .btn--danger}
[Info Button Text](#link){: .btn .btn--info}
[Inverse Button](#link){: .btn .btn--inverse}
[Light Outline Button](#link){: .btn .btn--light-outline}
```

[X-Large Button](https://www.google.com){: .btn .btn--primary .btn--x-large}
[Large Button](https://www.google.com){: .btn .btn--primary .btn--large}
[Default Button](https://www.google.com){: .btn .btn--primary }
[Small Button](https://www.google.com){: .btn .btn--primary .btn--small}

```markdown
[X-Large Button](#link){: .btn .btn--primary .btn--x-large}
[Large Button](#link){: .btn .btn--primary .btn--large}
[Default Button](#link){: .btn .btn--primary }
[Small Button](#link){: .btn .btn--primary .btn--small}
```

## 注意文字

**Watch out!** This paragraph of text has been [emphasized](#) with the `{: .notice}` class.
{: .notice}

**Watch out!** This paragraph of text has been [emphasized](#) with the `{: .notice--primary}` class.
{: .notice--primary}

**Watch out!** This paragraph of text has been [emphasized](#) with the `{: .notice--accent}` class.
{: .notice--accent}

**Watch out!** This paragraph of text has been [emphasized](#) with the `{: .notice--info}` class.
{: .notice--info}

**Watch out!** This paragraph of text has been [emphasized](#) with the `{: .notice--warning}` class.
{: .notice--warning}

**Watch out!** This paragraph of text has been [emphasized](#) with the `{: .notice--success}` class.
{: .notice--success}

**Watch out!** This paragraph of text has been [emphasized](#) with the `{: .notice--danger}` class.
{: .notice--danger}

## 超链接

This is an example of a [link](http://apple.com).

This is an example of a [link](http://apple.com "Apple").

## 内嵌代码

You will learn later on in these tests that `word-wrap: break-word;` will be your best friend.

## 删除线

This element will let you <strike>strikeout text</strike>.

## 倾斜

The emphasize element should _italicize_ text.

## 加粗

This element shows **bold text**.

## 下标

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

## 上标

Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.


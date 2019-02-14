# Markdown Cookbook

`Markdown` - **简洁的文档语言**

`Markdown` is a simple markup language that allows one to write documents using a text editor and transform those documents into many different formats.  Among other things, it works beautifully for documenting source code since the Markdown documents can be checked in and versioned with Git or your source control system of choice.

- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Writing on GitHub](https://help.github.com/categories/writing-on-github/)

## Table Of Content

- [Heading 标题](#heading-标题)
- [Paragraph 段落](#paragraph-段落)
- [List 列表](#list-列表)
  - [Unordered List 无序列表](#unordered-list-无序列表)
  - [Ordered List 有序列表](#ordered-list-有序列表)
- [Inline Code 内嵌代码](#inline-code-内嵌代码)
- [Image 图片](#image-图片)
- [Link 链接](#link-链接)
- [Text 文本](#text-文本)
  - [Bold Text 强调文本](#bold-text-强调文本)
  - [Italic Text 斜体文本](#italic-text-斜体文本)
  - [Deleted Text 删除文本](#deleted-text-删除文本)
  - [Combined Emphasis Text 混合文本](#combined-emphasis-text-混合文本)
- [Table 表格](#table-表格)
- [Horizontal Rule 水平分割线](#horizontal-rule-水平分割线)
- [Blockquote 引用块](#blockquote-引用块)
- [GitHub Flavored Markdown GitHub的Markdown拓展](#github-flavored-markdown-github的Markdown拓展)
  - [Code Block 代码段](#code-block-代码段)
  - [User Mention 用户提醒](#user-mention-用户提醒)
  - [Issue Reference Issue引用](#issue-reference-issue引用)
  - [Task List 任务清单](#task-list-任务清单)
  - [SHA-1 References 提交Hash引用](#sha-1-references-提交hash引用)
  - [Emoji 表情](#emoji-表情)

***

## Heading 标题

```markdown
# Level-1 Heading
## Level-2 Heading
### Level-3 Heading

# 一级标题
## 二级标题
### 三级标题
```

```html
<h1>Level-1 Heading</h1>
<h2>Level-2 Heading</h2>
<h3>Level-3 Heading</h3>

<h1>一级标题</h1>
<h2>二级标题</h2>
<h3>三级标题</h3>
```

## Paragraph 段落

```markdown
段落1

Paragraph2
```

```html
<p>段落1</p>
<p>Paragraph2</p>
```

## List 列表

### Unordered List 无序列表

```markdown
- Item 1
  - Item 1.1
  - Item 1.2
- Item 2

- 列表项目1
  - 列表项目1.1
  - 列表项目1.2
- 列表项目2
```

```html
<ul>
  <li>Item 1</li>
  <ul>
    <li>Item 1.1</li>
    <li>Item 1.2</li>
  </ul>
  <li>Item 2</li>
</ul>

<ul>
  <li>列表项目1</li>
  <ul>
    <li>列表项目1.1</li>
    <li>列表项目1.2</li>
  </ul>
  <li>列表项目2</li>
</ul>
```

### Ordered List 有序列表

```markdown
1. Item 1
1. Item 2

1. 列表项目1
1. 列表项目2
```

```html
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
</ol>

<ol>
  <li>列表项目1</li>
  <li>列表项目2</li>
</ol>
```

## Inline Code 内嵌代码

```markdown
`code here`
```

```html
<code>code here</code>
<value>code here</value>
```

## Image 图片

```markdown
![Alt Text](URL)

![替换文本](URL)
```

```html
<img src="URL" alt="Alt Text"/>

<img src="URL" alt="替换文本"/>
```

## Link 链接

```markdown
[Link Text](URL)
[Link Text](URL "Tip Text")

[链接文字](URL)
[链接文字](URL "提示文字")
```

```html
<a href="URL">Link Text</a>
<a href="URL" title="Tip Text">Link Text</a>

<a href="URL">链接文字</a>
<a href="URL" title="提示文字">链接文字</a>
```

## Text 文本

### Bold Text 强调文本

This text will be **bold**

This will also be __bold__

这是**强调文字**

这不支持中文__强调文字__

```markdown
This text will be **bold**

This will also be __bold__

这是**强调文字**

这不支持中文__强调文字__
```

```html
This text will be <strong>bold</strong>

This will also be <strong>bold</strong>

这是<strong>强调文字</strong>

这不支持中文<strong>强调文字</strong>
```

### Italic Text 斜体文本

```markdown
*This text will be italic*
_This will also be italic_

*次强调文字， 斜体*
_这也是次强调文字，斜体_
```

```html
<em>This text will be italic</em>
<em>This will also be italic</em>

<em>次强调文字， 斜体</em>
<em>这也是次强调文字，斜体</em>
```

### Deleted Text 删除文本

~~Deleted Text~~

~~删除的文字~~

```markdown
~~Deleted Text~~

~~删除的文字~~
```

```html
<del>Deleted Text</del>

<del>删除的文字</del>
```

### Combined Emphasis Text 混合文本

Combined emphasis with **asterisks and _underscores_**.

混合的文本**强调和 _斜体_**.

```markdown
Combined emphasis with **asterisks and _underscores_**.

混合的文本**强调和 _斜体_**.
```

```html
Combined emphasis with <strong>asterisks and <em>underscores</em></strong>.

混合的文本<strong>强调和 <em>斜体</em></strong>.
```

## Table 表格

| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |

```markdown
| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |
```

```html
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Help</td>
      <td>Display the help window.</td>
    </tr>
    <tr>
      <td>Close</td>
      <td>Closes a window</td>
    </tr>
  </tbody>
</table>
```

## Horizontal Rule 水平分割线

```markdown
***
```

```html
<hr/>
```

## Blockquote 引用块

As Kanye West said:

> We're living the future so
> the present is our past.

```markdown
As Kanye West said:

> We're living the future so
> the present is our past.
```

```html
<p>As Kanye West said:</p>

<blockquote>We're living the future so
  the present is our past.</blockquote>
```

## GitHub Flavored Markdown GitHub的Markdown拓展

**G**ithub **F**lavored **M**arkdown = **GFM**

### Code Block 代码段

<!-- markdownlint-disable MD031 -->
```markdown
```python
print ('Hello world')
``` // end
```
<!-- markdownlint-enable MD031 -->

```html
<code>
print ('Hello world')
</code>
```

### User Mention 用户提醒

```markdown
@user
```

### Issue Reference Issue引用

```markdown
#issue

#1
<repo>#1
<user>/<repo>#1
```

### Task List 任务清单

```markdown
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> are supported
- [x] list syntax is required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

- [x] 已完成
- [x] 已完成
- [x] 已完成
- [ ] 未完成
```

### SHA-1 References 提交Hash引用

Any reference to a commit’s `SHA-1 hash` will be *automatically* converted into a link to that commit on GitHub.

```markdown
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
```

### Emoji 表情

Refer to [GitHub Emoji](https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji).

```markdown
:+1: :shipit:
```

:+1: :shipit:

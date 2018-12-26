# Markdown Cookbook

`Markdown` - **简洁的文档语言**

- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Writing on GitHub](https://help.github.com/categories/writing-on-github/)

## Table Of Content

- [Heading 标题]("#Heading-标题")
- [Paragraph 段落]("#Paragraph-段落")
- [List 列表]("#List-列表")
  - [Unordered List 无序列表]("#Unordered-List-无序列表")
  - [Ordered List 有序列表]("#Ordered-List-有序列表")
- [Inline Code 内嵌代码]("#Inline-Code-内嵌代码")
- [Image 图片]("#Image-图片")
- [Link 链接]("#Link-链接")

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

## 文本

```markdown
**强调文字**
*次强调文字*
~~删除的文字~~
```

```html
<strong>强调文字</strong>
<em>次强调文字</em>
<del>删除的文字</del>
```

## 表格

```markdown
| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |
```

```html
<table>
</table>
```

## 分割线
```markdown
***
```

```html
<hr/>
```

## Markdown拓展

### 代码段

```markdown
```python
print ('Hello world')
```//end
```

```html
<code>
print ('Hello world')
</code>
```

### 用户

```markdown
用户
@user

任务
#issue
```

### 任务清单

```markdown
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> are supported
- [x] list syntax is required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```

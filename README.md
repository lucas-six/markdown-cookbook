# Markdown Cookbook

简单、高效的文档标记语言

## 标题

```markdown
# 一级标题
```

```html
<h1>一级标题</h1>
```

```markdown
## 二级标题
```

```html
<h2>二级标题</h2>
```

```markdown
### 三级标题
```

```html
<h3>三级标题</h3>
```

## 段落

```markdown
段落1

段落2
```

```html
<p>段落1</p>
<p>段落2</p>
```

## 列表

```markdown
- 列表项目1
  - 列表项目1.1
  - 列表项目1.2
- 列表项目2
```

```html
<ul>
  <li>列表项目1</li>
  <ul>
    <li>列表项目1.1</li>
    <li>列表项目1.2</li>
  </ul>
  <li>列表项目2</li>
</ul>
```

## 代码段

```markdown
```python
print 'Hello world'
```//end
```

```html
<code>
print 'Hello world'
</code>
```

## 嵌入代码

```markdown
`code here`
```

```html
<code>code here</code>
<value>code here</value>
```

## 链接

```markdown
[链接文字](URL)
[链接文字](URL "提示文字")
```

```html
<a href="URL">链接文字</a>
<a href="URL" title="提示文字">链接文字</a>
```

## 强调

```markdown
**强调文字**
*次强调文字*
```

```html
<strong>强调文字</strong>
<em>次强调文字</em>
```

## 用户

```markdown
@user
```

## Issue

```markdown
#issue
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

## 任务清单

```markdown
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> are supported
- [x] list syntax is required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```

## 参考资料

- [Writing on GitHub](https://help.github.com/categories/writing-on-github/)
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

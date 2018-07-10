# Markdown Cookbook

`Markdown` - **简洁的文档语言**

- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Writing on GitHub](https://help.github.com/categories/writing-on-github/)

## 标题

```markdown
# 一级标题
## 二级标题
### 三级标题
```

```html
<h1>一级标题</h1>
<h2>二级标题</h2>
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

## 嵌入代码

```markdown
`code here`
```

```html
<code>code here</code>
<value>code here</value>
```

## 图片

```markdown
![替换文本](URL)
```

```html
<img src="URL" alt="替换文本">
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

---
sort: 1
---

# Markdown 语法

文本样式可以是 **加粗**, _斜体_, 或者 ~~删除线~~. [链接](https://github.com)。

段落之间需要有空行。

段落之间需要有空行。

> 块引用的第一行不能有空行。
>
> 块引用的文本是灰色背景，并且引用文本需要有左边缘线。
>
> 块引用的最后不能有空行。

# 一级标题

这是标题下的一段正常段落。

## 二级标题

> 这是标题下的块引用.

### 三级标题

```
这是标题下的代码块。
```

#### 四级标题

- 这是无序列表项
- 这是无序列表项
- 这是无序列表项

##### 五级标题

1. 这是有序列表
2. 这是有序列表
3. 这是有序列表

###### 六级标题

| What    | Follows  |
| ------- | -------- |
| A table | A header |
| A table | A header |
| A table | A header |

---

水平分割线如上下

---

任务清单如下:

- [x] Create a sample markdown document
- [x] Add task lists to it
- [ ] Take a vacation

混合的任务清单如下：

- [ ] Steal underpants
- ?
- [ ] Profit!

嵌套的无序列表:

- Jackson 5
  - Michael
  - Tito
  - Jackie
  - Marlon
  - Jermaine
- TMNT
  - Leonardo
  - Michelangelo
  - Donatello
  - Raphael

也可以使用HTML语法定义列表。默认的样式为加粗和斜体。

<dl>
    <dt>Name</dt>
    <dd>Godzilla</dd>
    <dt>Born</dt>
    <dd>1952</dd>
    <dt>Birthplace</dt>
    <dd>Japan</dd>
    <dt>Color</dt>
    <dd>Green</dd>
</dl>

---

表格是粗体标题，表格体行之间阴影交替。

| Artist          | Album          | Year |
| --------------- | -------------- | ---- |
| Michael Jackson | Thriller       | 1982 |
| Prince          | Purple Rain    | 1984 |
| Beastie Boys    | License to Ill | 1986 |

如果某一数据行过多，它应该向下换行压缩和/或水平滚动。

<!-- prettier-ignore-start -->

| Artist            | Album           | Year | Label       | Awards   | Songs     |
|-------------------|-----------------|------|-------------|----------|-----------|
| Michael Jackson   | Thriller        | 1982 | Epic Records | Grammy Award for Album of the Year, American Music Award for Favorite Pop/Rock Album, American Music Award for Favorite Soul/R&B Album, Brit Award for Best Selling Album, Grammy Award for Best Engineered Album, Non-Classical | Wanna Be Startin' Somethin', Baby Be Mine, The Girl Is Mine, Thriller, Beat It, Billie Jean, Human Nature, P.Y.T. (Pretty Young Thing), The Lady in My Life |
| Prince            | Purple Rain     | 1984 | Warner Brothers Records | Grammy Award for Best Score Soundtrack for Visual Media, American Music Award for Favorite Pop/Rock Album, American Music Award for Favorite Soul/R&B Album, Brit Award for Best Soundtrack/Cast Recording, Grammy Award for Best Rock Performance by a Duo or Group with Vocal | Let's Go Crazy, Take Me With U, The Beautiful Ones, Computer Blue, Darling Nikki, When Doves Cry, I Would Die 4 U, Baby I'm a Star, Purple Rain |
| Beastie Boys      | License to Ill  | 1986 | Mercury Records | noawardsbutthistablecelliswide | Rhymin & Stealin, The New Style, She's Crafty, Posse in Effect, Slow Ride, Girls, (You Gotta) Fight for Your Right, No Sleep Till Brooklyn, Paul Revere, Hold It Now, Hit It, Brass Monkey, Slow and Low, Time to Get Ill |

<!-- prettier-ignore-end -->

---

像代码段 `var foo = "bar";` 应该在行内输入。

同样的，`this should vertically align` ~~`with this`~~ ~~and this~~.

代码片段也可以放在代码块中。

```
var foo = "bar";
```

代码段也可以使用高亮语法，标注的语言和代码匹配就可以高亮

```javascript
var foo = "bar";
```

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```javascript
var foo =
  "The same thing is true for code with syntax highlighting. A single line of code should horizontally scroll if it is really long.";
```

表格单元格内的内联代码仍然可以区分。

| Language   | Code               |
| ---------- | ------------------ |
| Javascript | `var foo = "bar";` |
| Ruby       | `foo = "bar"`      |

---

小图像应该显示在他们的实际大小。

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

大图片应该总是按比例缩小并适合内容容器。

![Branching](https://guides.github.com/activities/hello-world/branching.png)

# Markdown 全元素测试文档

## 基础文本样式

这是**加粗文字**，这是*斜体文字*，这是~~删除线~~，这是`行内代码`，这是[链接示例](https://example.com)，这是键盘输入：<kbd>Ctrl+S</kbd>

## 标题测试

# H1 标题

## H2 标题

### H3 标题

#### H4 标题

##### H5 标题

###### H6 标题

## 列表测试

### 无序列表

- 一级列表
  - 二级嵌套列表
    - 三级嵌套列表
- 项目包含多种样式：
  - **加粗项**
  - _斜体项_
  - ~~删除项~~

### 有序列表

1. 第一项
2. 第二项
   1. 嵌套有序项
   2. 另一个嵌套项
3. 第三项

## 代码块测试

```javascript
function helloWorld() {
  console.log('Hello, World!')
  const num = 123
  return num.toString(16)
}
```

```python
def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        yield a
        a, b = b, a + b
```

## 表格测试

| 功能   | 语法           | 效果      | 状态    |
| ------ | -------------- | --------- | ------- |
| 加粗   | `**text**`     | **示例**  | 支持 ✅ |
| 斜体   | `*text*`       | _示例_    | 支持 ✅ |
| 代码块 | `code`         | `代码`    | 支持 ✅ |
| 链接   | `[title](url)` | [示例](#) | 支持 ✅ |

## 多媒体元素

![替代文字](https://picsum.photos/600/400 '图片标题')

<https://example.com>（自动链接测试）

## 引用块测试

> 一级引用文本
>
> > 嵌套引用文本
>
> 包含**加粗**和`代码`的引用

## 分割线测试

---

---

## 特殊元素

### 任务列表

- [x] 已完成任务
- [ ] 未完成任务
  - [ ] 嵌套任务

### 脚注测试

这是一个带脚注的文本[^1]，另一个脚注[^2]

[^1]: 第一个脚注内容
[^2]: 第二个脚注内容（包含**格式**和`代码`）

### 数学公式

$$
f(x) = \int_{-\infty}^\infty \hat f(\xi)\,e^{2 \pi i \xi x} \,d\xi
$$

行内公式：$E = mc^2$

### 定义列表

术语 1
: 定义内容 1

术语 2
: 定义内容 2
: 第二个定义

## 混合内容测试

1. **列表项包含**：
   - 嵌套无序列表
   - `代码` 和 ![小图标](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAHElEQVQI12P4//8/w38GIAXDIBKE0DHxgljNBAAO9TXL0Y4OHwAAAABJRU5ErkJggg==)
2. 表格中的特殊内容：
   | 列 1 | 列 2 |
   |-----|-----|
   | `代码` | **加粗** |
   | $x^2$ | ![小图标](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAHElEQVQI12P4//8/w38GIAXDIBKE0DHxgljNBAAO9TXL0Y4OHwAAAABJRU5ErkJggg==) |

## 长文本测试

这是非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常长的文本，测试自动换行和行高设置。

这是非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常非常长的文本，测试自动换行和行高设置。

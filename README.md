这是一份严格按照 **GitHub Flavored Markdown (GFM)** 标准编写的示例文件。你可以将其直接复制到 Obsidian 中，作为你的格式基准（Benchmark）。

---

# 1 GFM 完整语法示例

## 1.1 标题 (Headings)

# 2 一级标题

## 2.1 二级标题

### 2.1.1 三级标题

#### 2.1.1.1 四级标题

##### 2.1.1.1.1 五级标题

###### 2.1.1.1.1.1 六级标题

---

## 2.2 文本格式 (Emphasis)

**粗体 (Bold)**

_斜体 (Italic)_

**_粗斜体 (Bold & Italic)_**

~~删除线 (Strikethrough)~~

---

## 2.3 列表 (Lists)

### 2.3.1 无序列表

- 项目 A
    - 子项目 A 1
    - 子项目 A 2

- 项目 B

- 项目 C

### 2.3.2 有序列表

1. 第一步
2. 第二步
    1. 嵌套步骤 2 a
    2. 嵌套步骤 2 b

### 2.3.3 任务列表 (Task Lists)

- [x] 已完成任务
- [ ] 未完成任务
- [ ] 待办项 3

---

## 2.4 引用与呼出框 (Blockquotes & Alerts)

> 这是一个标准的块引用。
>
> > 这是一个嵌套的块引用。

> [!NOTE]
> 这是一个提示信息

> [!TIP]
> 这是一个技巧提示

> [!IMPORTANT]
> 这是重要信息

> [!WARNING]
> 这是警告信息

> [!CAUTION]
> 这是危险警告

---

## 2.5 代码 (Code)

### 2.5.1 行内代码

使用 `git commit` 提交代码。

### 2.5.2 代码块 (Syntax Highlighting)

```cpp
#include <iostream>

int main(){
return 0;
}
```

---

## 2.6 表格 (Tables)

| Lab  | Lab  | lab | lab  | lab  |
| ---- | ---- | --- | ---- | ---- |
| Text | Text | lok | sdsd | lskc |
|      |      |     |      |      |

---

## 2.7 链接与图片 (Links & Images)

超链接 Markdown 语法

- `[超链接显示名](超链接地址 "超链接title")`

[链接名称](https://www.typedefyang.cn '主页')

使用尖括号可以很方便地把 URL 或者 email 地址变成可点击的链接。

- `<https://www.example.com>`
- `example@gmail.com`

<https://www.example.com>

<example@gmail.com>

图片的显示在链接格式前添加 `!`

- `![超链接显示名](超链接地址 "超链接title")`

## 2.8 数学公式 (Mathematical Expressions)

行内公式：$a^2 + b^2 = c^2$

块级公式：

$$\frac{d}{dx} e^x = e^x$$

---

## 2.9 脚注 (Footnotes)

这是一个带有脚注的句子[^1]。

---

## 2.10 转义字符

以 backslash 开始，后面的字符将实际显示

- \*
- \(
- \#
- \@

等等

## 2.11 符号(Symbols)

- `&copy;` (版权符号 ©)
- `&reg;` (注册商标符号 ®)
- `&trade;` (商标符号 ™)
- `&euro;` (欧元符号 €)
- `&larr;` (左箭头 ←)
- `&uarr;` (上箭头 ↑)
- `&rarr;` (右箭头 →)
- `&darr;` (下箭头 ↓)
- `&#176;` (度 °)
- `&#960;` (圆周率 π)


## 2.12 其他 github 可用

+ 新增项
- 删除项



---

[^1]: 这是脚注

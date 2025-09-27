---
layout: null
title: "Markdown demo" 
permalink: /demo/ 
---
# Markdown 进阶语法与面前题学习笔记


### 1.1 表格

| 问题类型 | 学习内容 | 知识点（例） |
| :--- | :---: | ---: |
| **Markdown 语法** | 表格 | `:---`（左对齐）、`:---:`（居中）、`---:`（右对齐） |

### 1.2 今日任务

- [x] 前往面试
- [ ] 完成面试

### 1.3 脚注的使用示例

Markdown 可以方便地添加脚注来提供补充信息，见[ 1.3 脚注的使用示例](# 1.3 脚注的使用示例)。

**原神[^genshin]**

[^genshin]:《原神》是由米哈游自主研发的一款全新开放世界冒险游戏。游戏发生在一个被称作「提瓦特」的幻想世界，在这里，被神选中的人将被授予「神之眼」，导引元素之力。你将
扮演一位名为「旅行者」的神秘角色，在自由的旅行中邂逅性格各异、能力独特的同伴们，和他们一起击败强敌，找回失散的亲人——同时，逐步发掘「原神」的真相。

### 2.1 Python代码块


```python
#计算阶乘的递归函数
def factorial(n):
    if n == 1:
        return 1
    return n * factorial(n-1)
```


### 2.2 折叠

<details>
<summary><b>点击展开：关于面前题</b></summary>
<br>
面试题真是让人酣畅淋漓
</details>

### 2.3 内嵌 HTML 与 CSS

<style>
body {
    font-size: 25px;
}
</style>

<p style="background: linear-gradient(90deg, #f093fb 0%, #f5576c 100%); padding: 1rem; border-radius: 8px; color: white; text-align: center;">
<strong>我的天呐！</strong> 我真是越来越厉害了
</p>


---
*文档创建于：2025年9月*
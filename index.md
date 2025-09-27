---
layout: null
title: 廖敬轩的自我介绍
---

<style>
/* === 基础样式 === */
body {
    line-height: 2;
    color: #000000;
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    font-family: 'Microsoft YaHei', sans-serif;
}
.header {
    text-align: center;
    margin-bottom: 2rem;
    border-bottom: 2px solid rgba(9, 105, 218, 1);
    padding-bottom: 1rem;
}
.name {
    font-size: 2.5rem;
    font-weight: bold;
    color: #0969da;
    margin-bottom: 0;
}
.description {
    font-size: 1.2rem;
    color: #666;
    text-align: center;
}
.contact-info {
    background-color: #f9f9ff;
    padding: 1rem;
    border-radius: 8px;
    margin: 2rem 0;
}
.contact-info a {
    color: #0969da;
}

/* === 页面切换样式 === */
.page-container {
    position: relative;
    min-height: 500px;
}

.page {
    display: none;
    width: 100%;
    opacity: 0;
    transition: opacity 0.5s ease-in-out;
}

.page.active {
    display: block;
    opacity: 1;
}

.page-nav {
    text-align: center;
    margin-top: 2rem;
    padding-top: 1rem;
    border-top: 1px solid #eee;
}

.page-btn {
    padding: 10px 25px;
    margin: 0 10px;
    background-color: #0969da;
    color: white;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    font-size: 1rem;
    transition: background-color 0.3s;
}

.page-btn:hover:not(:disabled) {
    background-color: #0752b3;
}

.page-btn:disabled {
    background-color: #cccccc;
    cursor: not-allowed;
}

#page-indicator {
    margin: 0 15px;
    font-weight: bold;
    color: #666;
}

/* === Markdown内容样式 === */
.markdown-content h1 {
    font-size: 2.2rem;
    color: #0969da;
    border-bottom: 2px solid #eee;
    padding-bottom: 0.3rem;
    margin-top: 2rem;
}

.markdown-content h2 {
    font-size: 1.8rem;
    color: #0969da;
    margin-top: 1.8rem;
}

.markdown-content h3 {
    font-size: 1.5rem;
    margin-top: 1.5rem;
}

.markdown-content blockquote {
    border-left: 4px solid #0969da;
    padding-left: 1rem;
    margin-left: 0;
    color: #555;
    background-color: #f9f9f9;
    padding: 1rem;
    border-radius: 0 4px 4px 0;
}

.markdown-content pre {
    background-color: #f6f8fa;
    border: 1px solid #e1e4e8;
    border-radius: 6px;
    padding: 16px;
    overflow-x: auto;
    margin: 1rem 0;
}

.markdown-content code {
    font-family: 'Courier New', monospace;
    font-size: 0.9em;
}

.markdown-content table {
    width: 100%;
    border-collapse: collapse;
    margin: 1rem 0;
}

.markdown-content th, .markdown-content td {
    border: 1px solid #dfe2e5;
    padding: 8px 12px;
    text-align: left;
}

.markdown-content th {
    background-color: #f6f8fa;
    font-weight: bold;
}

.markdown-content ul, .markdown-content ol {
    padding-left: 2rem;
    margin: 1rem 0;
}

.markdown-content li {
    margin: 0.3rem 0;
}
</style>

<div class="header">
    <div class="name">廖敬轩</div>
    <div class="description">自动化类2503</div>
</div>

<!-- 页面容器 -->
<div class="page-container">
    <!-- 第一页：自我介绍 -->
    <div class="page active" id="page1">
        <p>您好！欢迎访问我的个人主页。</p>
        <p>我有很多爱好，喜欢尝试新事物，其中擅长演播和唱歌。</p>
        <p>热爱编程与技术，有python基础，能编写简单程序，如排序、链表、解密等。</p>
        <p>但只简单深入，了解一些pandas数据处理，web开发框架等知识。</p>
        <p>正在学习c++，css，html，javascript等语言，有python基础因此学起来相对轻松，已经基本了解，正在熟练掌握ing...</p>
        <p>也在学习Linux等其他面前题中涉及到的知识点。</p>
        <p>运用GitHubPage制作简单网页时还了解到了YAML，简单学习之后发现计算机简直是个无底洞！这一眼就是多少个新单词在等待着我啊喂</p>
        <p>完蛋更感兴趣了。。。</p>

        <div class="contact-info">
            <h2>联系方式</h2>
            <p>outlook邮箱: <a href="mailto:liaojingxuan1@outlook.com">liaojingxuan1@outlook.com</a></p>
            <p>QQ邮箱: <a href="mailto:2642781501@qq.com">2642781501@qq.com</a></p>
        </div>
    </div>

    <!-- 第二页：Markdown示例 -->
    <div class="page" id="page2">
        <div class="markdown-content">
            {% capture markdown_content %}
# Markdown 语法全功能示范

本文档综合展示了 Markdown 的基本语法和进阶用法。

## 1. 基本语法示范

### 标题系统
Markdown 支持六级标题，使用 `#` 数量表示级别。

### 段落与字体格式
段落之间用空行分隔。支持**粗体**、*斜体*、***粗斜体***、~~删除线~~。

### 列表展示
- **无序列表**：使用 `-`、`*` 或 `+`
  - 编程语言
    - Python
    - JavaScript
- **有序列表**：
  1. 安装编辑器
  2. 学习基础语法
  3. 实践练习

### 链接
- [百度](https://www.baidu.com)

## 2. 进阶语法应用

### 表格创建
| 语言 | 学习难度 | 应用领域 |
| :--- | :---: | ---: |
| Python | 低 | Web开发、数据分析 |
| C++ | 高 | 系统编程、游戏 
### 扩展元素
- **待办列表**：
  - [x] 前往面试
  - [ ] 完成面试
- **上下标**：
  化学式：H~2~O | 数学平方：X^2^
            {% endcapture %}
            {{ markdown_content | markdownify }}
        </div>
    </div>
</div>

<!-- 导航按钮 -->
<div class="page-nav">
    <button class="page-btn" id="prev-btn" disabled>‹ 上一页</button>
    <span id="page-indicator">1 / 2</span>
    <button class="page-btn" id="next-btn">下一页 ›</button>
</div>

<script>
// 页面切换逻辑
let currentPage = 1;
const totalPages = 2;
const prevBtn = document.getElementById('prev-btn');
const nextBtn = document.getElementById('next-btn');
const pageIndicator = document.getElementById('page-indicator');

function updateButtons() {
    prevBtn.disabled = (currentPage === 1);
    nextBtn.disabled = (currentPage === totalPages);
    pageIndicator.textContent = `${currentPage} / ${totalPages}`;
}

function goToPage(pageNum) {
    if (pageNum < 1 || pageNum > totalPages) return;
    
    document.getElementById(`page${currentPage}`).classList.remove('active');
    document.getElementById(`page${pageNum}`).classList.add('active');
    
    currentPage = pageNum;
    updateButtons();
}

prevBtn.addEventListener('click', () => goToPage(currentPage - 1));
nextBtn.addEventListener('click', () => goToPage(currentPage + 1));
updateButtons();
</script>
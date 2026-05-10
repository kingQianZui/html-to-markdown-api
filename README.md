# 🌐 HTML to Markdown API

> **Instantly convert any webpage into clean, structured Markdown.**

<p align="center">
  <a href="https://rapidapi.com/qianzui/html-to-markdown" target="_blank">
    <img src="https://img.shields.io/badge/RapidAPI-Try%20it%20Free!-brightgreen?style=for-the-badge&logo=rapidapi" alt="Try on RapidAPI">
  </a>
  <a href="https://markdownapi.ccwu.cc" target="_blank">
    <img src="https://img.shields.io/badge/Status-Online-brightgreen?style=for-the-badge" alt="Status">
  </a>
</p>

---

## ✨ Features

- ✅ **Convert Any Webpage**: From simple articles to complex news sites, it just works.
- ✅ **Clean Output**: Automatically strips away JavaScript, CSS, and other non-content elements.
- ✅ **Built for AI**: Perfect for feeding clean, structured text to **AI Agents**, **RAG pipelines**, and **LLMs**.
- ✅ **Fast & Simple**: A single `POST` request is all it takes.

---

## 🚀 Quick Start

### 1. Get Your API Key
Subscribe to a plan (including a **Free** tier) on RapidAPI to get your unique API key:
👉 **[Get API Key on RapidAPI](https://rapidapi.com/qianzui/html-to-markdown)**

### 2. Make Your First Request

Copy and paste this into your terminal:

```bash
curl -X POST "https://markdownapi.ccwu.cc/api/fetch" \
  -H "Content-Type: application/json" \
  -H "x-api-key: YOUR_API_KEY" \
  -d '{"url": "https://example.com"}'
3. Get Clean Markdown
Response (200 OK):

json
{
  "success": true,
  "url": "https://example.com",
  "markdown": "# Example Domain\n\nThis domain is for use in ...",
  "remaining_quota": 99
}
📖 Full API Reference
Endpoint	Method	Description
/api/fetch	POST	Converts a webpage URL to Markdown
Request Body (JSON):

Parameter	Type	Required	Description
url	string	Yes	The full URL of the webpage to convert
Headers:

Header	Value
Content-Type	application/json
x-api-key	Your API key
🛠️ Tech Stack
Runtime: Cloudflare Workers

Database: Supabase

API Hub: RapidAPI

💰 Plans
You can try it out for free, and upgrade as you grow:

Plan	Price	Requests/Month
Free	$0.00	100
Pro	$9.99	10,000
Ultra	$49.99	100,000
👉 View All Plans & Subscribe

📢 Feedback & Questions
Found a bug? Have a feature request? Just want to say hi?

💬 Open an Issue

🐦 Twitter: @你的Twitter账号

Happy building! 🎉

text

---

## 📍 粘贴到这里（在 GitHub 上操作）

1. 浏览器打开 `https://github.com/你的用户名/html-to-markdown-api`

2. 如果仓库里**已经有** `README.md`：
   - 点击 `README.md` 文件名
   - 点击右上角 **铅笔图标 ✏️**
   - 把里面原来的内容**全删掉**
   - **粘贴**上面复制的文案

3. 如果仓库里**还没有** `README.md`：
   - 点击 **「Add file」** 按钮
   - 点击 **「Create new file」**
   - 文件名输入：`README.md`
   - 在下面的大编辑框里**粘贴**上面复制的文案

4. 拉到页面最底部，点击绿色 **「Commit changes」** 按钮

---

## ✅ 完成

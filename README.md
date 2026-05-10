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

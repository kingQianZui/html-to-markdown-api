# 🌐 HTML to Markdown API

> Instantly convert any webpage into clean, structured Markdown.

---

## ✨ Features

- **Convert Any Webpage**: From simple articles to complex news sites, it just works.
- **Clean Output**: Automatically strips away JavaScript, CSS, and other non-content elements.
- **Built for AI**: Perfect for feeding clean, structured text to AI Agents, RAG pipelines, and LLMs.
- **Fast & Simple**: A single POST request is all it takes.

---

## 🚀 Quick Start

### 1. Get Your API Key
Subscribe to a plan (including a Free tier) on RapidAPI to get your unique API key:
https://rapidapi.com/qianzui/html-to-markdown

### 2. Make Your First Request
Copy and paste this into your terminal:

curl -X POST "https://markdownapi.ccwu.cc/api/fetch" -H "Content-Type: application/json" -H "x-api-key: YOUR_API_KEY" -d '{"url":"https://example.com"}'

text

### 3. Get Clean Markdown
Response (200 OK):
{
"success": true,
"url": "https://example.com",
"markdown": "# Example Domain\n\nThis domain is for use in ...",
"remaining_quota": 99
}

text

---

## 📖 API Reference

| Endpoint | Method | Description |
|----------|--------|-------------|
| /api/fetch | POST | Converts a webpage URL to Markdown |

### Request Body (JSON)
| Parameter | Type | Required | Description |
|-----------|------|----------|-------------|
| url | string | Yes | The full URL of the webpage to convert |

### Headers
| Header | Value |
|--------|-------|
| Content-Type | application/json |
| x-api-key | Your API key |

---

## 🛠️ Tech Stack

- Runtime: Cloudflare Workers
- Database: Supabase
- API Hub: RapidAPI

---

## 💰 Plans

| Plan | Price | Requests/Month |
|------|-------|---------------|
| Free | $0.00 | 100 |
| Pro | $9.99 | 10,000 |
| Ultra | $49.99 | 100,000 |

Subscribe here: https://rapidapi.com/qianzui/html-to-markdown/pricing

---

## 📢 Feedback & Questions

Found a bug? Have a feature request?

Open an Issue: https://github.com/千首王/HTML转MarkdownAPI/issues

---

Happy building! 🎉

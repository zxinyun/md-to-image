<div align="center">

# Markdown To Image Serve

[![license](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)
[![Node Version](https://img.shields.io/node/v/next.svg)](https://nodejs.org)
[![Issues](https://img.shields.io/github/issues/your-username/markdown-to-image-serve.svg)](https://github.com/wxingheng/markdown-to-image-serve/issues)

<h4>Markdown to Image Service based on Next.js and Puppeteer, supporting Docker one-click deployment and API integration</h4>
<p>Efficiently convert Markdown content into beautiful images, with ready-to-use API endpoints, Docker quick deployment, and support for secondary development.</p>
[简体中文](./README.md) | English

</div>

---

## 🎯 Project Introduction

![Example 1](https://github.com/user-attachments/assets/a0e641b8-9369-4cc6-b602-256f26089777)
![Example 3](https://github.com/user-attachments/assets/e5e4ac59-a607-42d7-9d47-180eb7fe2268)

---

## 🌟 Core Features

- 📝 One-click Markdown to image
- 🎨 Multiple themes and custom styles
- 📊 Code highlighting and table rendering
- 🖼️ Custom headers and footers
- 📱 Responsive output for multiple devices
- 🔄 Batch conversion capability
- 📦 Comprehensive API support

---

## 📚 API Documentation

### 1. Generate Poster (POST `/api/generatePosterImage`)

**Request Parameters:**

```json5
{
  "markdown": "string",       // Markdown content
  "header": "string",         // Optional: header text
  "footer": "string",         // Optional: footer text
  "logo": "string",           // Optional: logo image url
  "theme": "blue | pink | purple | green | yellow | gray | red | indigo | SpringGradientWave" // Optional: theme
}
```

**Example Request:**

```bash
curl -X POST 'http://localhost:3000/api/generatePosterImage' \
  -H 'Content-Type: application/json' \
  -d '{
    "markdown": "# Hello World\n\nThis is a test. \n # Hello, World!",
    "header": "My Header",
    "footer": "My Footer"
  }'
```

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

Thanks to the [markdown-to-image](https://github.com/gcui-art/markdown-to-image) project for inspiration.

If this project helps you, please star to support! ⭐️

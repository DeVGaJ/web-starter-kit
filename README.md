# web-starter-kit

# 🕸️ Web Starter Kit

A curated collection of ready-to-use static website templates, utility snippets, and a bonus minimal HTTP server written in **C**.

> **Purpose:** To provide building blocks for common website features like e-commerce, catalogs, WhatsApp integrations, and blog layouts without the bloat of heavy frameworks.
This repo provides building blocks for common website features: e-commerce product pages, catalogs, WhatsApp API integration, blog layouts, newsletter signup forms, etc. The C example demonstrates a minimal HTTP server for serving static files.

---

## 📂 Folder Structure

```text
web-starter-kit/
├── README.md
├── ecommerce/
│   ├── index.html          # Product listing page
│   ├── product.html        # Single product page
│   └── style.css
├── catalog/
│   ├── index.html          # Grid catalog layout
│   └── style.css
├── whatsapp-api/
│   ├── index.html          # Form to send WhatsApp message via API
│   ├── script.js           # Fetch API call to WhatsApp API (demo)
│   └── style.css
├── blog/
│   ├── index.html          # Blog homepage with posts
│   ├── post.html           # Single post template
│   └── style.css
├── newsletter/
│   ├── index.html          # Signup form with email input
│   └── style.css
├── c-http-server/
│   ├── server.c            # Minimal HTTP server in C (serves static files)
│   ├── Makefile
│   └── www/                # Place HTML files here
│       └── index.html
└── assets/                 # Shared images, icons, etc.

```
🚀 Quick Start
1. Using the Templates
Simply navigate to any folder (e.g., ecommerce) and open index.html in your browser. These are pure HTML/CSS/JS—no installation required.
2. Running the C HTTP Server
If you want to test your static files using a real low-level server:
```bash
cd c-http-server
make
./server
```
The server will start on port 8080 (default). Place your HTML files inside c-http-server/www/.

📦 Installation
Clone the repository to get started:
```bash
git clone [https://github.com/DeVGaJ/web-starter-kit.git](https://github.com/DeVGaJ/web-starter-kit.git)
cd web-starter-kit
```
created by DeVGaJ

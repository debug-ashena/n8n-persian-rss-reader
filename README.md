# n8n-persian-rss-reader
An open-source agent for reading and translating the state-of-the-art technology news around IT, AI , and CyberSecurity. The news is engaging sysadmins, web hosting technical support teams, and all web-hosting companies.

# Persian RSS News Reader Workflow for n8n

An automated n8n workflow that fetches multiple Persian and tech RSS feeds (like WordPress, Cloudflare, HackerNews), processes and summarizes the content using AI, and publishes/delivers the results smoothly.

## Features
- 🔄 Automated RSS Feed Fetching
- 🤖 AI Content Summarization & Processing
- ⏱️ Smart Rate Limiting & Flow Control (Wait & Filter nodes)
- 🚀 Telegram/Notification integration ready

## Prerequisites
- n8n (Self-hosted via Docker recommended)
- PostgreSQL (or standard n8n database)
- AI Provider API Key (OpenAI / AvalAI / etc.)

## Installation & Setup
1. Download the JSON workflow file from this repository (`rss-workflow.json`).
2. Import the workflow into your n8n dashboard.
3. Configure your credentials:
   - RSS / HTTP Request nodes
   - AI Model Node credentials
   - Telegram Bot Token / Chat ID (or your preferred output node)
4. Adjust the Filter and Wait nodes according to your posting frequency (e.g., 3600 seconds delay).

## License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.



# ورک‌فلو خبرخوان RSS فارسی برای n8n

یک ورک‌فلو خودکار در n8n که فیدهای RSS فارسی و تکنولوژی (مانند وردپرس، کلادفلر، هکرنیوز) را دریافت کرده، محتوا را با استفاده از هوش مصنوعی پردازش و خلاصه‌سازی می‌کند و نتایج را به صورت روان منتشر و ارسال می‌نماید.

## ویژگی‌ها
- 🔄 **دریافت خودکار فیدهای RSS**
- 🤖 **خلاصه‌سازی و پردازش محتوا با هوش مصنوعی**
- ⏱️ **کنترل جریان و محدودسازی نرخ هوشمند** (با استفاده از نودهای Wait و Filter)
- 🚀 **آماده برای یکپارچه‌سازی با تلگرام** و سایر سیستم‌های اطلاع‌رسانی

## پیش‌نیازها
- ابزار **n8n** (نصب به صورت Self-hosted روی Docker توصیه می‌شود)
- دیتابیس **PostgreSQL** (یا دیتابیس پیش‌فرض n8n)
- کلید API ارائه‌دهنده هوش مصنوعی (مانند OpenAI، AvalAI و غیره)

## نصب و راه‌اندازی
1. فایل JSON ورک‌فلو را از این مخزن دانلود کنید (`rss-workflow.json`).
2. ورک‌فلو را به داشبورد n8n خود Import کنید.
3. حساب‌های کاربری و Credentials مورد نیاز را پیکربندی کنید:
   - نودهای RSS / درخواست‌های HTTP
   - اعتبارنامه‌های نود مدل هوش مصنوعی
   - توکن ربات تلگرام / Chat ID (یا نود خروجی دلخواه خود)
4. نودهای Filter و Wait را بر اساس فرکانس انتشار دلخواه خود تنظیم کنید (مثلاً تأخیر ۳۶۰۰ ثانیه‌ای برای هر پست).

## مجوز (License)
این پروژه تحت **مجوز MIT** منتشر شده است - برای جزئیات بیشتر فایل [LICENSE](LICENSE) را مطالعه کنید.


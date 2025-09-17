# 🌌 Quoteverse API

![Cover Photo](https://res.cloudinary.com/ds64xs2lp/image/upload/v1752863761/Quoteverse_xekg7v.png)

> **A Consciousness-Powered Quotes API**  
> 🌍 28,693+ curated quotes across 17+ themes · 100+ translation languages supported

---

## 🔗 Live Links

- 🔥 **GitHub Repo**: [github.com/dakidarts/quoteverse-api](https://github.com/dakidarts/quoteverse-api)  
- 🚀 **RapidAPI Page**: [rapidapi.com/kidddevs/api/quoteverse](https://rapidapi.com/dakidarts-dakidarts-default/api/quoteverse)  
- 📖 **Official API Docs**: [dakidarts.com/api/quoteverse-api](https://dakidarts.com/api/quoteverse-api)  
- 🌐 **Supported Languages (Google Translate)**: [cloud.google.com/translate/docs/languages](https://cloud.google.com/translate/docs/languages)

---

## ✨ What is Quoteverse?

**Quoteverse** is a REST API that serves deep, mindful, motivational, and inspirational quotes across **21 powerful categories**, including:

- Good Morning, Good Night, Good Afternoon
- Love, Courage, Success, Healing
- Stoicism, Spirituality, Mindfulness
- African, American & Asian Proverbs
- Affirmations, Poetic & Wisdom Quotes

Each quote request delivers one **random quote**, and optionally, a **translated version** in any of the 100+ supported languages using Google Translate.

---

## 📦 Features

- ✅ Over **28,000 unique quotes**
- 🌍 Supports **100+ languages** with Google Translate
- 🔄 Returns a new **random quote** each request
- 🧘‍♂️ Themes that awaken, inspire & elevate
- 🧩 Supports both `GET` and `POST` requests
- 🧼 Clean, readable JSON responses
- ⚡ Fast and lightweight

---

## 🔧 API Usage

### Request

```bash
GET /inspirational
GET /gratitude?lang=fr
POST /good-night with JSON body: { "lang": "es" }
````

### Response (if `lang` is set)

```json
{
  "original_quote": "Peace comes from within. Do not seek it without.",
  "quote": "La paz viene de adentro. No la busques afuera.",
  "target_language": "es"
}
```

### Response (if no `lang` provided or `lang = en`)

```json
{
  "quote": "Peace comes from within. Do not seek it without."
}
```

---

## 🧠 Available Endpoints (v0.0.1 - Seed Dropper)

```
GET /good-morning
GET /good-afternoon
GET /good-night
GET /affirmations
GET /consciousness
GET /courage
GET /gratitude
GET /healing
GET /inspirational
GET /love
GET /mindfulness
GET /motivational
GET /poetic
GET /spiritual
GET /stoicism
GET /success
GET /thoughtful
GET /wisdom
GET /proverbs/african
GET /proverbs/american
GET /proverbs/asian
```

Each endpoint also supports `POST` with optional `"lang": "<ISO-639 code>"`.

---

## 🌐 Language Support

You can pass the query parameter `lang=<language_code>` (e.g., `fr`, `es`, `de`, `sw`, etc.) to translate the quote.
Check supported codes here:
🔗 [Google Translate Language Codes](https://cloud.google.com/translate/docs/languages)


---

## ⚡️ Stay Connected

> ✨ Powered by [Dakidarts](https://x.com/dakidarts)
> ✍️ Quotes published daily via [Quoteverse X Account](https://x.com/Quoteverse369)

---

> **Let the quotes you serve not only inspire minds, but awaken souls.**
> — *Quoteverse*

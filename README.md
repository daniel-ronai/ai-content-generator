# 🛠️ AI Content Generator (Make.com Scenario)

This Make.com automation generates long-form content outlines based on structured form inputs using GPT-4 and stores the output in Google Docs. It’s designed to turn brief ideas into usable, structured articles — fast.

---

## 🔄 Workflow Overview

1. **Form Submission (Typeform)**  
   Collect content prompts like:
   - Title
   - Word count
   - Primary + secondary keywords
   - Internal/external links
   - Additional instructions

2. **Save to Google Sheet**  
   The submission is saved for logging, analysis, or review.

3. **Retrieve Latest Entry**  
   The automation grabs the newest entry to generate the content.

4. **AI-Powered Generation (GPT-4)**  
   It formats the data into a JSON brief and sends it to OpenAI GPT-4 to generate a **Markdown-based outline**.

5. **Markdown to Google Doc**  
   The output is compiled and sent to Google Docs for clean delivery.

---

## ⚙️ Tech Stack

- **Make.com** (Scenario automation)
- **Typeform** (Input collection)
- **Google Sheets** (Data store)
- **OpenAI GPT-4** (Text generation)
- **Google Docs** (Output format)

---

## 📦 What You’ll Need

- A Make.com account
- Connections to:
  - Typeform (or replace with another form service)
  - Google Sheets + Google Docs
  - OpenAI (GPT-4 model)
- A Typeform with relevant fields set up (title, keywords, etc.)

---

## 🚀 How to Use

1. **Set up your accounts** (Google, Typeform, OpenAI)
2. **Import the scenario file** into Make.com
3. **Replace placeholder connections** with your own
4. **Map your Typeform fields** to the variables
5. **Run the scenario or set it to trigger automatically**

---

## 📁 Included Files

- `Content-Gen.blueprint.json` → The cleaned Make.com scenario (connections removed)
- `README.md` → This documentation

---

## 💡 Notes

- This is a **stripped-down version**. In production, I use enhanced prompt chaining, error handling, and doc styling.
- You can extend this to:
  - Auto-publish to Notion or WordPress
  - Summarize or repurpose the content
  - Generate multiple formats (tweet, thread, blog)

---

## 🙌 Created by [Daniel Rónai](https://x.com/danielronai)  
Let me know if you build with it — or want a more advanced version.

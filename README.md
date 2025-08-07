# 🛒 AI Assistant for Grocery Inventory Management

A smart, AI-powered assistant designed to simplify grocery inventory management. Built using **n8n** for workflow automation, **Google Sheets** for data storage, and **OpenAI** for intelligent, conversational interaction — this project helps reduce manual effort and provides real-time stock insights via natural language queries.

---

## 📌 Project Objectives

- ✅ Automate grocery inventory tracking and reduce manual data entry.
- 💬 Allow users to interact with inventory data using natural language.
- 📊 Enable real-time stock updates and visibility.
- 🔐 Provide basic authentication to secure access.

---

## 🛠️ Tech Stack

| Tool          | Role                                                                 |
|---------------|----------------------------------------------------------------------|
| **n8n**       | Workflow orchestration (webhooks, API calls, integration handling)   |
| **Google Sheets** | Primary database for inventory data (read/write in real-time)       |
| **OpenAI API**| Natural language understanding & response generation                 |
| **Basic Auth**| Simple access control to secure the webhook                         |

---

## 🧠 How It Works (Architecture)

1. **User Query**: User sends a message via the AI assistant interface (webhook).
2. **Webhook Trigger**: n8n receives and processes the input.
3. **Sheet Query**: n8n fetches inventory details from Google Sheets.
4. **OpenAI Processing**: User input and sheet data are sent to OpenAI for interpretation and response generation.
5. **Reply**: The assistant responds with relevant inventory info (stock level, expiry date, etc).

---

## 🔐 Access Info (Demo)

> ⚠️ **For demo purposes only. Replace credentials before production use.**

- **AI Assistant URL**: [Click to Access](https://dollyjessy.app.n8n.cloud/webhook/e8122e41-b3be-4f98-9f5a-07ca005e17ed/chat)
- **Username**: `admin`
- **Password**: `1234`

---

## 📝 Sample Queries

Try typing:
- `"How many apples are in stock?"`
- `"Show me the list of items, we have in stock"`
- `"Update the bread stock to 15 units"`

---

## 🚀 Future Enhancements

- Advanced user authentication (OAuth/JWT)
- Integration with barcode scanners for stock entry
- Visual dashboards for analytics
- Voice-based assistant interface
- Alerts for low stock and expiry

---

## PDF Report File

Created using **[Gamma.app](https://gamma.app/?utm_source=made-with-gamma)**  



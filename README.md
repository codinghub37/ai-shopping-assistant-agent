# 🛒 AI Shopping Assistant Agent

An AI-powered Shopping Assistant that helps users discover products and place orders using natural language or product images. Built with **LangChain**, **Groq LLM**, **Streamlit**, **SQLite**, and **Vision AI**, the assistant can search products, retrieve customer ratings, analyze uploaded images, and complete purchases through an intelligent conversational interface.

---

## 🚀 Features

- 🛍️ Natural language product search
- 🖼️ Shop by product image
- 🤖 AI-powered product recommendations
- ⭐ Customer ratings and reviews
- 💰 Price-based filtering
- 🌱 Organic product filtering
- 📦 SQLite product database
- 🛒 Order placement through AI agent
- 💻 Interactive Streamlit web interface

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Groq LLM
- SQLite
- Pillow
- Python Dotenv

---

## 📁 Project Structure

```text
ai-shopping-assistant-agent/
│
├── app.py
├── shopping_agent.py
├── reviews_api.py
├── setup_db.py
├── store.db
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
│
└── resources/
    ├── sample_image_1.jpg
    ├── sample_image_2.jpg
    └── sample_image_3.jpg
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/codinghub37/ai-shopping-assistant-agent.git
```

### Navigate to the Project

```bash
cd ai-shopping-assistant-agent
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root.

```env
GROQ_API_KEY=your_groq_api_key_here
```

---

## ▶️ Run the Application

If you don't already have the database, create it:

```bash
python setup_db.py
```

Then start the Streamlit application:

```bash
streamlit run app.py
```

---

## 🖼️ Shop by Image

The project includes a **resources/** folder containing sample product images.

Upload any image from this folder using the Streamlit sidebar, and the AI assistant will:

- Analyze the uploaded image
- Identify the product
- Search for similar products
- Display matching products with ratings and prices

---

## 💬 Example Queries

- I want organic honey under $20.
- Show me olive oil with a rating above 4.5.
- Find organic almonds.
- Recommend the best coffee.
- Order the first product.
- Buy product number 2.

---

## 📚 Workflow

1. User enters a product query or uploads a product image.
2. Vision AI analyzes the uploaded image.
3. The AI agent searches products in the SQLite database.
4. Customer ratings are retrieved automatically.
5. Matching products are displayed with prices and ratings.
6. User confirms the purchase.
7. The assistant places the order and saves it in the database.

---

## 🌟 Applications

- AI Shopping Assistant
- E-commerce Search
- Product Recommendation System
- Image-Based Product Search
- Conversational Commerce
- AI Retail Assistant
- Multimodal AI

---

## 📦 Database

The project includes a pre-built **SQLite** database (`store.db`) containing:

- Product catalog
- Customer reviews
- Product ratings
- Order history

To regenerate the database:

```bash
python setup_db.py
```

---

## 📦 Requirements

Install all dependencies using:

```bash
pip install -r requirements.txt

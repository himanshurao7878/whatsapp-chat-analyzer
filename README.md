# 📊 WhatsApp Chat Analyzer

An interactive data analysis web app that extracts insights from WhatsApp chat exports using **Python** and **Streamlit**.

---

## 🚀 Features

* 📈 **Top Statistics**

  * Total messages, words, media, and links 

* 📅 **Timeline Analysis**

  * Monthly and daily activity trends

* 📊 **Activity Insights**

  * Most active days and months
  * Weekly activity heatmap

* 👥 **User Analysis**

  * Most active users in the group
  * Contribution percentage

* ☁️ **Text Analysis**

  * Word cloud generation
  * Most common words

* 😀 **Emoji Analysis**

  * Most used emojis with visualization

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Pandas
* Matplotlib
* Seaborn
* WordCloud
* Regex (for chat parsing) 

---

## 📂 Project Structure

```
📁 whatsapp-chat-analyzer
│
├── app.py              # Main Streamlit app
├── helper.py           # Analysis & visualization functions
├── preprocessor.py     # Data cleaning & preprocessing
├── stop_hinglish.txt   # Stopwords file
├── .gitignore
```

---

## ▶️ How to Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the app

```bash
streamlit run app.py
```

---

## 📌 How to Use

1. Export your WhatsApp chat (without media)
2. Upload the `.txt` file in the app
3. Click **"Show Analysis"**
4. Explore insights 📊

---

## 🔍 How it Works

* Chat text is parsed using **regular expressions** 
* Messages are structured into a DataFrame
* Analysis functions compute stats, timelines, and patterns 
* Results are visualized using charts and heatmaps

---

## 🌟 Future Improvements

* Deploy app online (Streamlit Cloud)
* Add sentiment analysis
* Improve UI/UX
* Support multiple chat formats

---

## 👨‍💻 Author

**Himanshu Rao**

---

## ❤️ Acknowledgement

Inspired by real-world chat data analysis and data visualization concepts.



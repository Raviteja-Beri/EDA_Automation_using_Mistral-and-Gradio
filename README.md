# 📊 EDA Automation Using Mistral & Gradio

This project automates Exploratory Data Analysis (EDA) with the power of **LLMs (Mistral via Ollama)** and an interactive **Gradio** web interface. Upload any CSV dataset and instantly receive statistical summaries, AI-generated insights, and intuitive data visualizations — no coding required.

---

## 🚀 Features

- **🔍 Automated EDA:** Loads your dataset, fills missing values, and summarizes it.
- **🤖 AI-Powered Insights:** Uses the Mistral-7B model via Ollama to generate human-readable interpretations of your data.
- **📈 Visualizations:** Automatically generates histograms and correlation heatmaps.
- **🌐 Web Interface:** Simple Gradio UI to upload CSVs and view insights instantly.

---

## 📂 How It Works

1. **Upload your dataset (.csv).**
2. **EDA is performed:**
   - Missing values handled (median/mode/unknown).
   - Summary statistics generated.
   - AI generates insights from the summary.
   - Histograms and heatmaps are saved to `plots/`.
3. **Results shown:**
   - EDA Report (Text Summary + AI Insights).
   - Visual plots displayed in a gallery.

---

## 🛠️ Tech Stack

- **Frontend:** [Gradio](https://www.gradio.app/)
- **Backend:** Python
- **Data Handling:** Pandas
- **Visualization:** Matplotlib, Seaborn
- **AI Integration:** Ollama + Mistral-7B

---

## 🧪 Output
* Check the results or graphical output provided below the code in seperate folder.

## Thank You

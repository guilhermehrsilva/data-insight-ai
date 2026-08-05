# Data Insight AI

**Can an AI-powered platform automatically analyze any dataset and generate the right visualizations and KPIs?**

Self-service BI tool that uses Google Gemini to autonomously explore data, recommend KPIs, generate 30+ chart types, and answer business questions via natural language — all without writing code.

## Key Features

| Feature | Description |
|---------|-------------|
| 🤖 AI Analysis | Gemini auto-suggests KPIs and optimal charts based on data structure |
| 📊 Manual Builder | No-code interface with 30+ chart types (Waterfall, Funnel, Sankey, Gauge...) |
| 🩺 Data Health | Automated quality diagnostics (nulls, duplicates, reliability scores) |
| 💬 Chat Analytics | Ask business questions in natural language, get Plotly visualizations |
| 🔌 Hybrid Input | CSV, Excel uploads or direct MySQL connection |
| 🛡️ Fallback Mode | Charts still generate if the AI API goes down |

## Stack

`Python` · `Streamlit` · `Plotly` · `Google Gemini AI` · `Pandas` · `MySQL`

## How to Run

```bash
git clone https://github.com/guilhermehrsilva/data-insight-ai.git
cd data-insight-ai
pip install -r requirements.txt
streamlit run app.py
```

> Requires a Google Gemini API key configured as environment variable.

## Screenshot

![DataInsight AI Interface](front.png)

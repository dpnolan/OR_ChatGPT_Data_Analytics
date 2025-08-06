
# ChatGPT for Advanced Data Analysis – Webinar Exercises

This repository contains five hands-on Jupyter notebooks used in the **"ChatGPT for Advanced Data Analysis"** webinar. These exercises demonstrate how to combine traditional Python techniques with ChatGPT's API to analyze semi-structured, unstructured, behavioral, and time-series data.

---

## 📂 Contents

### Exercise 1  
**Analyzing Semi-Structured JSON Data with ChatGPT and Python**

### Exercise 2  
**Advanced NLP with ChatGPT API** — Extract structured metadata from support ticket comments.

### Exercise 3  
**ChatGPT-Powered NLP on Customer Support Tickets** — Compare traditional keyword classification with AI-powered insight extraction.

### Exercise 4  
**Behavioral Pattern Recognition with Python and ChatGPT** — Identify patterns from simulated behavioral logs using LLMs.

### Exercise 5  
**Time-Series Pattern Recognition and Forecasting with Python and ChatGPT** — Analyze sequences and project future behavior.

---

## 🛠️ Setup Instructions

Please refer to the [`Webinar_Setup_Instructions_ChatGPT.pdf`](Webinar_Setup_Instructions_ChatGPT%20for%20Advanced%20Data%20Analysis.pdf) for complete setup steps. Below is a summary:

### Option 1: Local Setup (Recommended)
1. Install [Anaconda](https://www.anaconda.com/products/distribution) with Python 3.8+
2. Create environment and install dependencies:
   ```bash
   conda create -n chatgpt_workshop python=3.8
   conda activate chatgpt_workshop
   conda install -c conda-forge notebook
   pip install openai tqdm
   conda install pandas numpy matplotlib seaborn requests scikit-learn geopandas
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

### Option 2: Google Colab
1. Open [Google Colab](https://colab.research.google.com)
2. Upload and run any `.ipynb` notebook
3. Install packages:
   ```python
   !pip install openai pandas numpy matplotlib seaborn tqdm
   ```

---

## 🔑 Using the OpenAI API
1. Sign up: https://platform.openai.com/signup  
2. Generate key: https://platform.openai.com/account/api-keys  
3. Paste the key inside notebook cells where prompted.

---

## 🧠 Note
- Ensure internet access is available for API calls.
- Run each notebook from top to bottom.
- Contact the presenter in advance for help—no troubleshooting will be done during the live session.

---

Happy Learning! 🚀

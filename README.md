# ResearchRadar

**ResearchRadar** is a content-based **research paper recommendation system**.  
It uses **TF-IDF vectorization** and **cosine similarity** to recommend academic papers based on their textual similarity, helping students, researchers, and professionals quickly discover relevant literature.  

Unlike citation-based systems, CiteGeist focuses purely on the *content* of the papers, ensuring that newer but relevant works are not overlooked.

---

## 🚀 Features

- 📄 **Content-Based Filtering** — Recommends papers by analyzing text similarity.
- 📊 **TF-IDF & Cosine Similarity** — Industry-standard NLP techniques for vectorization and comparison.
- ⚡ **Lightweight and Fast** — Minimal dependencies, quick recommendations.
- 🕵️ **No Tracking** — Does not rely on user behavior or personal data.
- 🎯 **Relevant Results** — Finds similar research beyond citation networks.

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Scikit-learn** — TF-IDF vectorizer, cosine similarity
- **Pandas / NumPy** — Data handling and processing
- **Flask or Django** — Web interface (depending on repo setup)
- **HTML/CSS/JavaScript** — Frontend

---

## 📥 Installation

```bash
# 1. Clone the repository
git clone https://github.com/Geoff-Robin/CiteGeist.git
cd CiteGeist

# 2. (Optional) Create a virtual environment
python -m venv venv
# Activate the virtual environment
# On Linux/Mac:
source venv/bin/activate
# On Windows:
venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

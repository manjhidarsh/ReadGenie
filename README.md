# ReadGenie 📚  
**LLM-Based Book Recommender System**

ReadGenie is a smart recommendation system powered by Large Language Models (LLMs). It analyzes book metadata, user reviews, sentiments, and text embeddings to suggest books users are most likely to enjoy.

---

## 🚀 How It Works

ReadGenie combines traditional recommendation strategies with the power of LLMs to deliver accurate and personalized book recommendations:

1. **Data Exploration**  
   Explore the dataset to understand user preferences, book popularity, and review patterns.

2. **Sentiment Analysis**  
   Analyze user reviews to capture the emotional tone using NLP techniques. Positive or negative sentiments help in fine-tuning recommendations.

3. **Text Classification**  
   Classify books or reviews into categories (e.g., genre or topic) using machine learning models for better filtering.

4. **Vector Search with Embeddings**  
   Use vector representations of books (e.g., using sentence-transformers or similar models) to find semantically similar books.

5. **Book Recommender Engine**  
   Based on all of the above, generate top-N recommendations tailored to a user's preferences or search query.

---

## 📁 Project Structure

ReadGenie/
├── book-recommender.py           # Main script for generating recommendations
├── data-exploration.ipynb        # EDA and preprocessing
├── sentiment-analysis.ipynb      # Sentiment analysis on reviews
├── text-classification.ipynb     # Text classification models
├── vector-search.ipynb           # Semantic similarity search using vectors


---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/manjhidarsh/LLM_Based_Recomender_sys.git
cd LLM_Based_Recomender_sys

### 2. Set Up Environment

python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
pip install -r requirements.txt

## 💡 Usage

1.Run notebooks in the following order:

   - data-exploration.ipynb

   - sentiment-analysis.ipynb

   - text-classification.ipynb

   - vector-search.ipynb

2.Use book-recommender.py to generate final recommendations.

# zomato-data-analysis
🚀 Zomato Restaurant Recommendation System – Bengaluru 🍽️
A content-based recommendation system built using Zomato restaurant data from Bengaluru, India. This project helps users discover top-rated restaurants based on cuisine preferences, location, and customer reviews.

📊 Project Features
Data Cleaning & Preprocessing:

Removed redundant columns, handled missing values, and standardized data formatting.

Applied TF-IDF vectorization on cuisines for content similarity.

Content-Based Recommendation System:

Recommends similar restaurants based on cuisine preferences.

Sorts by rating, votes, and location for accurate suggestions.

Flexible Filtering:

Search by cuisine type (e.g., North Indian, Chinese, Italian).

Displays price range, rating, and vote count for comparison.

Distance-Based Search:

Filter restaurants within a specific distance radius.

Scalable & Efficient:

Uses cosine similarity to find similar restaurants efficiently.

🔥 Tech Stack
Python 🐍

Pandas & NumPy for data cleaning & preprocessing

Scikit-Learn for TF-IDF Vectorization & Cosine Similarity

Google Colab for notebook execution

📚 How to Use
Clone the repository:

bash
Copy
Edit
git clone <repository_link>
Install required libraries:

nginx
Copy
Edit
pip install pandas numpy scikit-learn
Run the Jupyter/Colab notebook:

nginx
Copy
Edit
jupyter notebook zomato_recommendation.ipynb
Enter your preferred cuisine or restaurant name to get recommendations.

📈 Future Enhancements
Add collaborative filtering for personalized recommendations.

Integrate with Zomato API for real-time restaurant data.

Build a web app for easy access to recommendations.


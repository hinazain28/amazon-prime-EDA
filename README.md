# Amazon Prime Video EDA Project

This project is a beginner-friendly **Exploratory Data Analysis (EDA)** on an Amazon Prime dataset from Kaggle. It includes deep dives into content types, country availability, actor networks, and content similarity — all built and visualized using Python in Google Colab.

---

## Dataset

- **Source:** [Kaggle - Amazon Prime Dataset](https://www.kaggle.com/datasets)
- **Columns include:** Title, Description, Genre, Cast, Country, Date Added, Type (Movie/TV Show), etc.

---

## Project Goals

1. **Explore global content distribution** on Amazon Prime by country.
2. **Identify similar shows/movies** using descriptions and text-based features (TF-IDF + Cosine Similarity).
3. **Analyze actor and director collaborations** using network graphs.
4. **Visualize Prime’s focus over time** — has it shifted from Movies to TV Shows?

---

## EDA & Visualizations

- Top countries with most content available
- Content type trend (TV Shows vs Movies) over years using line and bar charts
- Content similarity engine using NLP (TF-IDF + Cosine Similarity)
- Actor collaboration network using `networkx`
- Tabular summary of all actors with number of co-actors and names

---

## Tools & Libraries Used

- Python
- Google Colab
- Pandas, Numpy
- Seaborn, Matplotlib, Plotly
- Scikit-learn (`TF-IDF`, `Cosine Similarity`)
- NetworkX
- TQDM

---

## How to Run

1. Open the Colab Notebook: [Click here](https://colab.research.google.com/drive/14-S48hRYRsPwQkR5uIrjvcYaInafcK3g)
2. Upload the Kaggle dataset
3. Run the cells one by one
4. Try modifying filters or testing new actor names in the network section

---

## Key Learnings

- Hands-on with real-world EDA in Python
- Introduction to content-based recommendation systems
- Practical use of text vectorization (TF-IDF)
- Building actor collaboration graphs using graph theory
- How to tell stories with data using clean visuals

---

## Future Improvements

- Add interactive widgets for filtering content
- Build a Streamlit app from this notebook
- Train a basic recommender model based on genres + ratings (if available)

---

## About Me

Hi! I'm **Hina**, an Electrical Engineering student exploring the world of data. This is one of my first real EDA projects — and it's just the beginning.

Feel free to connect or give feedback! 😊

---

## Contact

- GitHub: [hinazain28]
- Email: [hinazain28@gmail.com]

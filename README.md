# Ethan Radecki — Data Science Portfolio

**Live site:** [radeckiethan.github.io](https://radeckiethan.github.io/index.html)

M.S. Applied Data Science graduate from Syracuse University. This portfolio showcases seven data science projects spanning machine learning, natural language processing, sports analytics, econometrics, and full-stack web development.

---

## Site Structure

```
radeckiethan.github.io/
├── index.html                        # Main portfolio page
├── style.css                         # Shared styles across all pages
├── RadeckiEthan_Resume_May2026.pdf   # Downloadable resume
└── reports/
    ├── esg.html                      # ESG ratings project report
    ├── nba-roster-construction.html  # NBA project report
    ├── movies.html                   # Letterboxd project report
    ├── fantasy-football.html         # Fantasy football report
    ├── housing.html                  # Housing markets report
    ├── movie-review-sentiment.html   # Sentiment analysis report
    ├── cnn-emotion-music.html        # CNN emotion project report
    └── assets/                       # Images and data files for reports
```

---

## Projects

### Democratizing ESG: Predicting Corporate Sustainability Scores from Free Public Data
**Course:** IST 707 — Applied Machine Learning. Group project with Caden Lippie and John Masseria.

A machine learning pipeline that predicts corporate ESG scores using only freely available SEC 10-K filings and public EDGAR financial data, with no proprietary feeds, no prior ESG ratings, and no cost barrier. FinBERT sentiment features extracted from three 10-K narrative sections feed an ElasticNet regression model across 323 S&P 500 companies. The Social pillar achieved a holdout test R² of 0.215; Governance was structurally unpredictable from 10-K text alone.

`Python` `FinBERT` `ElasticNet` `SEC EDGAR API` `scikit-learn` `pandas`

---

### NBA Roster Construction & Salary Optimization
**Course:** Senior Thesis — Syracuse University, 2025

Three OLS regression models across 3,176 player-seasons and 420 team rosters (2011–2025) examine what drives NBA player contracts, which team playstyle indicators predict wins, and whether offense or defense matters more for team success. Data sourced from Basketball-Reference and RealGM.

`R` `Python` `OLS Regression` `Tableau` `Basketball-Reference` `RealGM`

---

### My Letterboxd in Numbers
**Course:** Personal Project

A personal analytics pipeline built on 704 rated films and 275 written reviews. TMDB API metadata enrichment feeds two machine learning models: an NLP model using TF-IDF and VADER sentiment, and a structured model using film properties. The NLP classifier achieves 62% accuracy versus a 48% majority-class baseline. VADER sentiment correlates only 0.16 with star ratings, and removing TMDB vote average from the structured model collapses performance to near zero.

`Python` `scikit-learn` `TF-IDF` `VADER` `Ridge Regression` `TMDB API` `Chart.js`

---

### Fantasy Sports Analytics Platform
**Course:** Personal Project — deployed live on Render

A full-stack fantasy football web application built from scratch transforming six seasons of league data into a live analytics platform. Features three original performance metrics (Dominance Score, Luck Score, Schedule Luck Rating), a weighted Euclidean distance similarity engine, a logistic regression playoff model (AUC 0.83), and 14 per-manager interactive dashboards.

`Python` `Flask` `Pandas` `Plotly` `Chart.js` `scikit-learn` `Bootstrap` `Render`

---

### Decoupling of U.S. Housing Markets from Economic Fundamentals
**Course:** IST 686 — Quantitative Reasoning for Data Science

Panel regression and Bayesian MCMC analysis across 5,840 observations from 20 U.S. metro regions (2000–2024) sourced from FRED. Both frequentist and Bayesian approaches confirm a 97% decline in unemployment sensitivity to housing prices by the Covid period, with the 95% Bayesian HDI for the Covid period containing zero.

`R` `Panel Regression` `Bayesian MCMC` `BayesFactor` `FRED Data` `cluster-robust SE`

---

### Movie Review Sentiment Analysis
**Course:** IST 664 — Natural Language Processing

Five-class sentiment classification on 156,060 Rotten Tomatoes phrases using progressive feature engineering. The best model combines bag-of-words, sentiment lexicons (LIWC + Subjectivity Lexicon), and custom negation handling with a Logistic Regression classifier under minimal preprocessing, achieving 58.1% accuracy and 55.3% F-1, a 7.7% accuracy improvement over baseline.

`Python` `NLTK` `scikit-learn` `Logistic Regression` `SVM` `LIWC` `Subjectivity Lexicon`

---

### Emotion to Music Recommender Using CNNs and OpenCV
**Course:** IST 691 — Deep Learning in Practice

A real-time pipeline that classifies facial expressions into one of seven emotions using a custom 4-block CNN trained on 35,887 FER-2013 images, then maps the result to a Spotify valence range for a mood-matched song recommendation. Achieved 37.1% live accuracy versus a 14.3% random baseline. Group project with Arya Patil and Caden Lippie.

`Python` `TensorFlow` `Keras` `OpenCV` `FER-2013` `Spotify API` `Haar Cascade`

---

## Tech Stack

| Area | Tools |
|---|---|
| Languages | Python, R, SQL |
| Machine Learning | scikit-learn, TensorFlow, Keras, XGBoost |
| NLP | NLTK, FinBERT, TF-IDF, VADER, LIWC |
| Data & Visualization | Pandas, NumPy, Plotly, Tableau, Chart.js, Matplotlib |
| Web | Flask, Bootstrap, HTML, CSS, JavaScript |
| Statistical Modeling | OLS Regression, ElasticNet, Panel Regression, Bayesian MCMC |
| APIs & Data Sources | SEC EDGAR, TMDB API, FRED, Basketball-Reference, RealGM, Spotify |
| Deployment | GitHub Pages, Render |

---

## Contact

- **Email:** ecradeck@syr.edu
- **LinkedIn:** [linkedin.com/in/ethan-radecki](https://www.linkedin.com/in/ethan-radecki/)
- **Phone:** (516) 385-7858

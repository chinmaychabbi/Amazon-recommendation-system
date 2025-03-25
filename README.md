# Amazon Product Recommendation System

##  Overview
This project presents a personalized product recommendation system tailored for Amazon’s extensive product catalog. The system leverages **content-based filtering**, a **partial matching algorithm**, and a **weighted scoring model** to provide relevant product suggestions based on individual user interaction history.

It was developed as part of the **CPTS 575: Data Science** course at **Washington State University**.

---

## 🛠 Tools & Technologies
- **Language**: R
- **Framework**: R Markdown
- **Libraries**: dplyr, ggplot2, stringdist, etc.
- **Data**: Amazon product and user interaction datasets
- **Platform**: RStudio

---

##  Methodology

The recommendation engine uses the following approach:

- **Content-Based Filtering**: Identifies product relevance based on user’s past actions (views, cart additions, purchases)
- **Partial Matching**: Aligns inconsistent product names using fuzzy matching (e.g., Levenshtein distance)
- **Weighted Scoring**: Combines popularity, ratings, and discounts using a custom scoring formula

###  Scoring Formula

```
Combined Score = 0.2 × Category Score 
               + 0.5 × Weighted Score 
               + 0.3 × Ratings
```

This ensures a personalized and value-driven recommendation list for each user.

---

##  Results

- The model achieved an average **recommendation accuracy of 35%**
- Top 5 recommendations were generated per user
- Visualizations and performance metrics validated model effectiveness

---

##  Project Structure

```
amazon-product-recommendation/
├── code/            # R Markdown project file
│   └── 575_project.Rmd
├── report/          # Final project report
│   └── DS_Report.pdf
├── ppt/             # Final presentation slides
│   └── DS_ppt.pdf
├── README.md        # Project overview (this file)
└── LICENSE          # Optional open-source license
```

---

##  My Role

I was responsible for:
- Designing and implementing the recommendation algorithm
- Cleaning, preprocessing, and engineering features from Amazon’s dataset
- Developing scoring logic and visualization
- Documenting insights and presenting the project

---

##  Documentation
- 📖 Full Report: [`DS_Report.pdf`](./report/DS_Report.pdf)
- 📊 Presentation: [`DS_ppt.pdf`](./ppt/DS_ppt.pdf)

---

##  License
This project is for academic and demonstration purposes. If reused, please provide appropriate credit. (Add an MIT License if open-sourcing.)

---

##  Contact
For questions or collaboration, feel free to connect via [LinkedIn](https://linkedin.com/in/chinmaychabbi) or GitHub.

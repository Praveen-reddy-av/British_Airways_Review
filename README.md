# ✈️ British Airways Review Analysis & Interactive Dashboard

## 📌 Project Overview  
This project analyzes real customer reviews of **British Airways** to uncover insights about customer satisfaction, service quality, and overall sentiment.  
A **Tableau Dashboard** has been created to visualize key metrics and trends, helping identify areas for improvement and understanding passenger experiences across different countries.

## 📂 Project Structure  
📁 British-Airways-Review-main
├── British Airways Review.twbx       # Tableau Dashboard / Workbook
├── ba_reviews.csv                    # Main dataset – customer reviews
├── Countries.csv                     # Country mapping dataset
├── README.md                         # Project documentation

## 🎯 Objectives  
- Analyze customer satisfaction from reviews  
- Perform sentiment-based categorization  
- Understand service quality across regions  
- Visualize rating trends and review distributions  
- Create a dynamic Tableau dashboard  

## 📊 Tableau Dashboard Insights  
| Dashboard Component | Description |
|---------------------|-------------|
| ⭐ Rating Distribution | Overall customer ratings |
| 😊 Sentiment Analysis | Positive / Neutral / Negative reviews |
| 🌍 Country-wise Map | Review origins & satisfaction trends |
| 🔑 Frequent Keywords | Common themes in reviews |
| ✈️ Cabin / Seat Class Analysis | Experience by travel class |
| 👨‍✈️ Service Category Breakdown | Food, Cabin crew, Comfort, Value for money |

## 🛠️ Technology Used
| Tool / Language | Purpose |
|-----------------|---------|
| Tableau | Dashboard & Visualizations |
| CSV / Excel | Data preprocessing |
| Python *(optional)* | Text cleaning or analysis |
| GitHub | Version control & documentation |

## 📥 Datasets
### 1. `ba_reviews.csv` – Customer Reviews
| Column | Description |
|-------|-------------|
| Date | Review date |
| Rating | Overall customer rating |
| Review | Written feedback |
| Seat Type | Economy / Business / First |
| Country | Country of reviewer |
| Recommended | Yes / No |

### 2. `Countries.csv` – Mapping Data
Used to map locations in Tableau when visualizing the review data.

## 🚀 How to Use the Project
### Option 1 – View Dashboard
1. Download the repository  
2. Open `British Airways Review.twbx` in Tableau  
3. Explore interactive dashboards & insights  

### Option 2 – Load Data in Python
```python
import pandas as pd
df = pd.read_csv("ba_reviews.csv")
print(df.head())
```

## 📈 Key Insights
✔ Business Class customers report higher satisfaction  
✔ Frequent complaints about **delays & customer service**  
✔ USA & UK have the most reviews  
✔ Comfort, food & cabin crew are dominant themes  
✔ Sentiment is mixed but **leaning slightly positive**

## 🔮 Future Enhancements
- Add **Python sentiment analysis (TextBlob, NLTK)**  
- Deploy on **Tableau Public with live link**  
- Create a **Power BI version** for comparison  
- Add **Machine Learning model** to predict sentiment from text  

## 📧 Contact  
**Author:** *Venkatapraveen Reddy Adireddy*  
- GitHub: *(Add your GitHub profile link here)*  
- LinkedIn: *(Add your LinkedIn profile link here)*  

⭐ If you find this project useful, please give it a star on GitHub!

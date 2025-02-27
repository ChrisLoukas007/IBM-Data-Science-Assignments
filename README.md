# 📌 IBM Data Science Assignments

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)](https://www.python.org/)  
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)](https://jupyter.org/)  
[![Machine Learning](https://img.shields.io/badge/Machine-Learning-green?style=for-the-badge&logo=scikit-learn)](https://scikit-learn.org/)

**🔬 A collection of data science assignments from IBM’s Data Science course.** This repository includes **data analysis, visualization, machine learning, and web scraping** projects completed during the coursework.

---

## 📂 Repository Structure

This repository is **organized by topic**, making it easy to navigate. Below is a breakdown of each section:

| 📁 Folder | 📝 Description |
|-----------|--------------|
| `Applied Data Science Capstone` | End-to-end data science project using SpaceX launch data. Includes web scraping, SQL, ML prediction. |
| `Data Analysis Process` | Step-by-step data analysis pipeline (cleaning, preprocessing, model evaluation). |
| `Data Visualization Process` | Advanced data visualization using **Matplotlib, Seaborn, Plotly, and Folium**. |
| `Machine Learning` | Supervised and unsupervised ML models such as **Decision Trees, K-Means, K-NN, Regression, SVM**. |

---

## 🚀 Key Highlights

✅ **Data Collection & Preprocessing**  
✔ Web scraping using `BeautifulSoup`  
✔ Data wrangling and cleaning (`Pandas`)  

✅ **Data Visualization**  
✔ Interactive visualizations (`Plotly`, `Folium`)  
✔ Advanced charting (`Seaborn`, `Matplotlib`)  

✅ **Machine Learning Models**  
✔ Regression: Linear, Multiple, Logistic  
✔ Clustering: K-Means, K-NN  
✔ Classification: Decision Trees, SVM  

✅ **Capstone Project: SpaceX Launch Analysis**  
✔ Extracting launch data using **APIs & Web Scraping**  
✔ Data Visualization of launch trends  
✔ Machine Learning to predict successful launches  

---

## 📊 Example Visualization

Here’s an example of **data visualization** from this project:

```python
import matplotlib.pyplot as plt
import seaborn as sns

# Sample Data
years = [2015, 2016, 2017, 2018, 2019, 2020]
success_rate = [50, 65, 72, 85, 90, 95]

# Plot
plt.figure(figsize=(8,4))
sns.lineplot(x=years, y=success_rate, marker="o", color="blue")
plt.title("🚀 SpaceX Launch Success Rate Over Years")
plt.xlabel("Year")
plt.ylabel("Success Rate (%)")
plt.show()
```

---

## 👅 Installation & Usage

To run these assignments locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/ChrisLoukas007/IBM-Data-Science-Assignments.git

# Navigate to the folder
cd IBM-Data-Science-Assignments

# Install dependencies (Recommended: Use virtual environment)
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
```

---

## 🛠 Tech Stack Used

🔹 **Programming Language**: Python  
🔹 **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `beautifulsoup4`, `plotly`, `folium`  
🔹 **Tools**: Jupyter Notebook, GitHub  

---

## 👨‍💻 Contribution

🚀 If you find this repository useful, feel free to **star ⭐ it** and contribute!  
📩 Open an **issue** or **pull request** for improvements.

---

## 📜 License

📝 This repository is licensed under the **MIT License**.

---

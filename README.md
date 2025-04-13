
# 🔥 FireDucks vs. Pandas: EDA & Visualization Benchmark 🐼

This project provides a side-by-side comparison of **FireDucks** and **Pandas** for performing Exploratory Data Analysis (EDA) and visualizations on a large-scale dataset (1 million rows).

---

## 📂 Repository Structure

```
fireducks-vs-pandas-eda/
├── large_dataset.csv                # Synthetic dataset with 1 million rows
├── fireducks_vs_pandas_eda.ipynb    # Jupyter notebook comparing FireDucks and Pandas
└── README.md                        # Project documentation
```

---

## 🚀 Getting Started

### 🔧 Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/yourusername/fireducks-vs-pandas-eda.git
cd fireducks-vs-pandas-eda
```

2. Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the dependencies:

```bash
pip install pandas fireducks matplotlib seaborn plotly jupyter
```

4. Launch the notebook:

```bash
jupyter notebook fireducks_vs_pandas_eda.ipynb
```

---

## 📊 Features

- 📥 CSV loading benchmarks
- 📈 Summary statistics using `describe()`
- 🔄 GroupBy aggregation comparisons
- 📉 Visualizations using Plotly and Matplotlib
- 🕒 Runtime comparisons between FireDucks and Pandas
- 🔧 Enabling FireDucks benchmark mode for performance insights

---

## 📸 Sample Visuals

| Tool      | Histogram Example |
|-----------|-------------------|
| Pandas    | ![pandas_hist](plots/pandas_hist.png) |
| FireDucks | ![fireducks_hist](plots/fireducks_hist.png) |

---

## 🧠 FAQs

**Q: What is FireDucks?**  
A high-performance, Pandas-compatible data analysis library optimized for large datasets.

**Q: What does benchmark mode do?**  
It logs execution time and memory usage for each operation automatically.

**Q: Does FireDucks work for smaller datasets?**  
Yes, but its speed advantage is best observed on larger datasets (e.g., >500k rows).

---

## 📎 License

This project is licensed under the MIT License.

---

## 🤝 Contributing

PRs and suggestions welcome! Feel free to open issues or share feedback.

---

## 📫 Contact

Reach out via GitHub or [LinkedIn](https://linkedin.com).

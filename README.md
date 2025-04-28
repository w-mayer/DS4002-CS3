# Does Emotional Sentiment Assist Email Spam Classification? Case Study for DS4002

This project introduces students to natural language processing with VADER to perform sentiment analysis on email text.

## Software and Platform
The analysis is run in Jupyter Notebooks.
Software: Python
Packages: for a full list, see [requirements.txt...](requirements.txt)

- Pandas
- Seaborn
- Scikit-learn
- VADER
- and more...

## Setup

To install dependencies:

```bash
git clone https://github.com/w-mayer/DS4002-CS3
cd post_visit_analysis
pip install -r requirements.txt
```

## Instructions

Start with the hook document! Then,
- View the make_data.ipynb and increase your sample size if you'd like.
- View eda.ipynb and add any visualizations you want to learn more about
- View analysis.ipynb and record your results!

## Repo Map
```
.
├── CS3-Hook.pdf: Start Here!
├── CS3-Rubric.pdf: Assignment rubric.
├── DATA/
│   ├── raw.csv: Full raw dataset
│   ├── sentiment.csv: Sample of 2,000 email texts and sentiment features
│   └── email.parquet: Established dataset for analysis
├── OUTPUT/
│   └── visualizations saved to .png files
├── SCRIPTS/
│   ├── make_data.ipynb: transform raw dataset into sampled final.parquet
│   ├── eda.ipynb: perform EDA and generate visualizations
│   └── analysis.ipynb: perform analysis and generate visualizations
└── REFERENCES/
    └── Supplementary reading material
```

## References:
[1] K. Bostoganashvili, “Spam Filters Explained [2025].” Accessed: Jan. 30, 2025. [Online]. Available: https://mailtrap.io/blog/spam-filters/

[2] Fortinet, Inc., “What is a Spam Filter & Spam Filtering?,” Fortinet. Accessed: Apr. 28, 2025. [Online]. Available: https://www.fortinet.com/resources/cyberglossary/spam-filters

[3] Oklahoma State University Stillwater, “Malicious Emails and Financial Scams - Oklahoma State University.” Accessed: Jan. 30, 2025. [Online]. Available: https://it.okstate.edu/resources/security-education/malicious-emails.html

[4] S. Sayyafzadeh, M. Weatherspoon, J. Yan, and H. Chi, “Securing Against Deception: Exploring Phishing Emails Through ChatGPT and Sentiment Analysis,” in 2024 IEEE/ACIS 22nd International Conference on Software Engineering Research, Management and Applications (SERA), 2024, pp. 159–165. doi: 10.1109/SERA61261.2024.10685564.

[5] A. Simha, “Understanding TF-IDF for Machine Learning,” Capital One. Accessed: Apr. 28, 2025. [Online]. Available: https://www.capitalone.com/tech/machine-learning/understanding-tf-idf/

What this notebook does
Loads a Kaggle dataset. It uses the Unicorn Companies dataset (CB Insights list of $1B+ startups) and keeps only the FinTech companies.
Classifies companies. Each company is put into one of the 7 FinTech categories and saved in a new Taxonomy column:
Payments & Digital Wallets
Digital Banking & Neobanks
Lending Tech & BNPL
WealthTech & Robo-Advisory
InsurTech
Blockchain & Crypto
RegTech
Compares Pakistani apps. A table of 8 Pakistani platforms (JazzCash, Easypaisa Bank, NayaPay, SadaPay, RAAST, Mashreq Bank Pakistan, HugoBank, Abhi) with their category, regulator and one key feature.
Visualizes the results. A matplotlib bar chart shows how many companies fall in each category.
Reflection. A short write-up connects the results to Pakistan's FinTech market.
Key findings
Payments & Digital Wallets is the largest category, both in the dataset and in Pakistan.
Blockchain & Crypto is big globally but almost missing in Pakistan.
WealthTech is under-represented in Pakistan, mainly because people have little money left to invest and still prefer gold, property and committees.
How to run
Open the notebook in Google Colab.
Click Runtime → Run all.
The dataset downloads automatically from Kaggle using kagglehub. If the download fails, the notebook uses a small built-in backup list so it still runs.
Tools used

Python · pandas · matplotlib · kagglehub · Google Colab

# Automated-negotiation-replication-package
Replication Package of the systematic mapping study on automated negotiation for intelligent agents

This study has been designed, developed, and reported by the following investigators:

- [Mashal Afzal Memon](https://scholar.google.com/citations?user=Mnu_k-8AAAAJ&hl=en) (University of L'Aquila, Italy)
- [Gian Luca Scoccia](https://scholar.google.com/citations?user=y8EX4DAAAAAJ&hl=en) (University of L'Aquila, Italy)
- [Marco Autili](https://scholar.google.com/citations?user=s8F7eWIAAAAJ&hl=en&oi=ao) (University of L'Aquila, Italy)

For any information, interested researchers can contact us by writing an email to [mashalafzal.memon@graduate.univaq.it](mailto:mashalafzal.memon@graduate.univaq.it)

# Structure of the replication package
This replication package is organized according to the following structure.

```
Root
│   readme.md                   # the file you are reading right now.
|   analysis                    # a folder containing exploration plots, raw data, and analysis scripts
|── output                      # a folder containing the working plots we used for exploring the extracted data
|── |── horizontal.pdf          # a PDF file containing the contingency tables we used for the horizontal analysis
|── |── barcharts.pdf           # a PDF file containing the bar charts we used for the horizontal analysis
|── rawData                     # a folder containing the raw data extracted from each primary study.
|── |── data.xlsx               # an Excel spreadsheet containing all the extracted data. There you will find a colum for each parameter of the data extraction form and a row for each primary study.
|── |── data.csv                # a comma-separated-value textual file created by exporting the extractedData.xlsx Excel spreadsheet 
└── scripts                     # a folder containing python scripts for analyzing the extracted data and for generating bar charts and contingency tables used for horizontal analysis. Each script is self-contained, it does not depend on other scripts, and has been executed via Google Colab.
```
 

# HanuAI Customer Feedback Analytics

End-to-end data analytics projects for turning customer feedback into actionable insights. This repository explores product reviews and consumer complaints through web scraping, sentiment analysis, exploratory data analysis, text mining, clustering, and visualization.

## Repository overview

The project is organized into independent tasks, with each task containing a Jupyter Notebook, supporting report, figures, and generated outputs where applicable.

### Task 1 — Best Buy reviews

`Task1_BestBuy_Reviews/` focuses on collecting and analyzing Best Buy product reviews.

- `Task1_BestBuy_Scraping_Sentiment.ipynb` — review scraping and sentiment-analysis workflow
- `Task1_Report.docx` — accompanying analysis report
- `figures/` — visualizations produced during the analysis
- `outputs/` — generated analysis outputs

### Task 2 — Exploratory data analysis and text mining

`Task2_EDA_TextMining/` focuses on exploring consumer-feedback data and extracting insights from text.

- `Task2_EDA_TextMining.ipynb` — exploratory analysis and text-mining workflow
- `Task2_Report.docx` — accompanying analysis report
- `data/` — input datasets
- `figures/` — visualizations produced during the analysis
- `outputs/` — generated analysis outputs

## Key analytical themes

- Web scraping and preparation of customer feedback
- Sentiment analysis of product reviews
- Exploratory data analysis and visualization
- Text preprocessing and feature extraction
- Identification of frequent terms and themes
- Clustering and segmentation of feedback
- Communicating findings through notebooks and written reports

## Getting started

### Prerequisites

- Python 3.9 or later
- Jupyter Notebook or JupyterLab
- Common data-analysis and natural-language-processing packages used by the notebooks

### Run the notebooks

1. Clone the repository:

   ```bash
   git clone https://github.com/Guru-Surya-Raja-J/HanuAI-customer-feedback-analytics.git
   cd HanuAI-customer-feedback-analytics
   ```

2. Launch Jupyter:

   ```bash
   jupyter notebook
   ```

3. Open either notebook:

   - `Task1_BestBuy_Reviews/Task1_BestBuy_Scraping_Sentiment.ipynb`
   - `Task2_EDA_TextMining/Task2_EDA_TextMining.ipynb`

4. Run the cells in order. Review each task's `data/`, `figures/`, and `outputs/` directories for the required inputs and generated artifacts.

> **Note:** If a notebook requires additional packages or external data, install or provide them according to the setup instructions documented inside that notebook.

## Outputs

The analyses produce charts, processed results, and supporting artifacts in the task-specific `figures/` and `outputs/` directories. The DOCX reports provide additional context and interpretation for each task.

## Responsible use and reproducibility

- Respect the terms of service and `robots.txt` policies of any website used for data collection.
- Avoid collecting unnecessary personal or sensitive information.
- Treat sentiment and clustering results as analytical signals rather than definitive judgments.
- Record data sources, collection dates, and preprocessing decisions when extending the project.

## Future enhancements

- Add a shared `requirements.txt` or `environment.yml` for reproducible setup.
- Add automated data-validation and notebook-execution checks.
- Provide interactive dashboards for exploring sentiment and themes.
- Expand the analysis to additional products, retailers, or complaint sources.

## License

No license has been specified for this repository yet. Unless a license is added, all rights are reserved by the repository owner.

Amazon Product Reviews — Data Cleaning and Exploratory Insights
Project Overview
This repository presents a carefully structured analysis of an Amazon product‑review dataset. The primary objectives were to verify data integrity, prepare the data for rigorous analysis, and conduct an exploratory review to understand customer‐rating behaviour and product popularity. All work was completed in Jupyter Notebook using Python and industry‑standard data‑science libraries, and the end‑to‑end process is fully documented for reproducibility.

Data Integrity and Preparation
The raw dataset was first examined for completeness and consistency. No missing values or duplicate records were detected, confirming a solid foundation for analysis. Ratings, originally stored as floating‑point numbers, were converted to integers to reflect the discrete nature of star scores. UNIX timestamps were transformed into ISO‑formatted date‑time values, enabling straightforward trend analysis. These steps ensured that every column was correctly typed and analytically ready.

Exploratory Analysis
With a clean dataset in place, the investigation proceeded to visualise rating distributions and identify the products that attract the highest levels of customer engagement. The distribution revealed a strong positive skew: five‑star reviews account for the majority of entries, indicating generally high customer satisfaction. Further inspection showed that a small subset of products consistently garners the greatest number of reviews, suggesting significant brand loyalty and robust market traction within that group.

Key Findings
The analysis confirms a reliable, high‑quality dataset and highlights enduring customer enthusiasm, as evidenced by the dominance of top ratings. Moreover, the concentration of review activity around a limited set of products underscores clear opportunities for targeted marketing and inventory optimisation.

Future Work
Building on these results, several extensions are planned. First, a collaborative‑filtering recommendation engine will leverage historical ratings to enhance cross‑sell and upsell strategies. Second, sentiment analysis of review text will provide granular insight into the specific product attributes that drive customer satisfaction or dissatisfaction. Finally, seasonality and category‐level trend studies will help refine marketing and supply‑chain decisions.

Technical Environment
All processing and visualisation were conducted in Python 3, using Pandas and NumPy for data manipulation and Matplotlib and Seaborn for charting. Version control is managed with Git and GitHub, ensuring transparent collaboration and reproducibility.


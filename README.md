# Twitter-Data-Analysis

## Project Description
This project analyzes Twitter data to understand user engagement patterns and optimize strategies for maximizing interaction. By exploring factors like hashtags, emojis, mentions, tweet length, posting time, and sentiment, it provides actionable insights for crafting engaging tweets. The dataset was self-scraped using Selenium and NTScraper, ensuring a comprehensive and authentic data source.

## Overview
Twitter is a microblogging platform where user engagement plays a crucial role in content visibility and influence. This project examines how different tweet attributes and posting patterns impact engagement metrics like likes, retweets, comments, and quotes. Key objectives include:
1. Understanding the influence of tweet characteristics (length, hashtags, mentions, emojis) on engagement.
2. Exploring the impact of posting time, day of the week, and sentiment on user interactions.
3. Providing recommendations for businesses and individuals to improve their Twitter strategies.

## Project Structure
- **Data Scraping**: Collected 23,000 tweets using Selenium and NTScraper from 2020 to 2024.
- **Exploratory Data Analysis (EDA)**: Examined trends in tweet engagement using descriptive statistics and visualizations.
- **Engagement Factor Analysis**: Analyzed the impact of hashtags, emojis, mentions, and timing on engagement levels.
- **Correlation Analysis**: Investigated relationships between tweet attributes and user interaction metrics.

## Project Files
- **data/twitter_data.csv**: Self-scraped dataset containing 23,000 tweets, including engagement metrics and other attributes.
- **scripts/Data_Scraping.ipynb**: Notebook detailing the scraping process using Selenium and NTScraper.
- **scripts/Twitter_Data_Analysis.ipynb**: Notebook containing data preprocessing, analysis, and visualizations.
- **report/Twitter_Data_Analysis_Report.pdf**: Project report summarizing methodology, findings, and conclusions.
- **README.md**: Project documentation (this file).

## Data Processing Steps
1. **Scraping**: Tweets were scraped from various business accounts, ensuring diversity in content and engagement metrics.
2. **Cleaning**: Removed NaN values and duplicates to ensure data quality.
3. **Normalization**: Engagement metrics were normalized by follower count to ensure fair comparisons.
4. **Feature Extraction**: Extracted hashtags, mentions, emojis, tweet length, and posting time for analysis.

## Key Findings
1. **Tweet Length**: Tweets longer than the average length (30 characters) received higher engagement, while shorter tweets were less effective.
2. **Hashtags**: Tweets with hashtags had significantly higher engagement, though overused hashtags were less impactful.
3. **Mentions**: Tweets without mentions slightly outperformed those with mentions, likely due to broader audience appeal.
4. **Emojis**: Tweets with 1–6 emojis showed higher engagement, while excessive use reduced effectiveness.
5. **Timing**: Tweets posted during weekends and early mornings (6–8 AM) saw the highest engagement levels.

## Dependencies
The following Python libraries are required:
- `selenium`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `datetime`
- `dateutil`
- `regex`

Install dependencies with:
```bash
pip install -r requirements.txt
```

## Results and Recommendations
- **Optimal Tweeting Times**: Early mornings and weekends maximize engagement. Businesses should consider scheduling tweets during these periods.
- **Content Strategy**: Use hashtags strategically and include visually appealing emojis. Avoid overloading tweets with mentions or hashtags.
- **User-Centric Approach**: Focus on creating engaging and contextually relevant content to resonate with a broader audience.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

For additional details, refer to the project report.

# 1mg-analysis-project








![328-246](https://github.com/bhratsharmaa/1mg-analysis-project/assets/132134997/d1c6f2ad-0f4a-40da-944e-7ae806939e76)










## Project Description:
In the era of data-driven decision-making, harnessing valuable insights from web data can be a game-changer for businesses. This project exemplifies the power of data acquisition, analysis, and visualization by leveraging web scraping techniques. Using the Python programming language and the BeautifulSoup library, we embarked on a journey to extract essential information from the 1mg website, a prominent online pharmaceutical and healthcare platform. Our objective was to transform raw web data into actionable insights that could drive informed decisions and bolster profitability.

## Project Highlights:
#### 1) Web Scraping and Data Extraction:
We initiated the project by employing BeautifulSoup to scrape crucial data from the 1mg website. This encompassed extracting data from tables, ensuring data integrity, and structuring it for further analysis.

#### 2) Data Transformation and Export:
To facilitate in-depth analysis, we seamlessly transformed the extracted data into an Excel spreadsheet. This step involved organizing columns, handling data types, and preparing the dataset for insightful exploration.

#### 3) Data Analysis and Visualization:
With the cleaned and structured dataset in hand, we delved into a comprehensive analysis. Employing data visualization libraries, such as Matplotlib and Seaborn, we crafted a series of informative charts, graphs, and visualizations. These visual representations unearthed trends, patterns, and correlations within the data, providing a deeper understanding of the pharmaceutical landscape.

#### 4) Dashboard Creation:
The pinnacle of our project was the creation of an interactive dashboard. Leveraging tools like Tableau or Power BI, we designed a user-friendly dashboard that encapsulated key findings, trends, and actionable insights derived from the data. This dashboard served as a one-stop hub for decision-makers to access critical information and make informed choices swiftly.

#### 5) Strategic Insights for Profitability:
Our analysis culminated in the generation of strategic insights. These insights encompassed market trends, product performance, pricing strategies, and customer behavior. By presenting these insights in a digestible format through our interactive dashboard, we equipped stakeholders with the tools needed to make data-driven decisions aimed at enhancing profitability and optimizing business operations.

This project exemplifies the fusion of web scraping, data analysis, and data visualization to convert raw web data into a valuable asset for decision-makers. By distilling complex information into actionable insights, we empower businesses to thrive in a competitive market landscape.


## Aim:
To harness the power of web scraping, data analysis, and data visualization techniques to transform raw data from the 1mg website into actionable insights and an interactive dashboard. The aim is to equip decision-makers in the pharmaceutical and healthcare domain with the tools and information needed to make informed choices, optimize pricing strategies, enhance product offerings, and ultimately increase profitability.


## Web scrapping 


#### This Python script scrapes product URLs from 1mg's homeopathy category, mimicking a web browser's behavior. It gathers these URLs for subsequent data collection and analysis.





<img width="711" alt="mg1" src="https://github.com/bhratsharmaa/1mg-analysis-project/assets/132134997/0e2d4812-be12-4a9e-8ba6-d98b7f6717e2">







#### This Python script sets a time limit for web scraping requests and initializes empty lists to store data such as product names, brand names, key benefits, key ingredients, product ratings, and the number of ratings. It iterates through a list of product URLs, sending HTTP GET requests to each product page and parsing the HTML content using BeautifulSoup. The script then extracts and stores information for each product, including its name, brand, key benefits, key ingredients, rating, and the number of ratings. It introduces a small delay between requests. Finally, it organizes the scraped data into a DataFrame for further analysis.




<img width="427" alt="mg1" src="https://github.com/bhratsharmaa/1mg-analysis-project/assets/132134997/00fd258a-bd5b-40f4-8527-c1c9c5702a41">









<img width="884" alt="mg2" src="https://github.com/bhratsharmaa/1mg-analysis-project/assets/132134997/128bacc7-40ec-4ef1-861a-4ad010d2c5f3">













## Visualizations:


#### Most popular Brands



<img width="654" alt="v1" src="https://github.com/bhratsharmaa/1mg-analysis-project/assets/132134997/5bfeb3c7-045b-483a-badb-a6182c3119ca">




#### Relationship between average rating and price 



<img width="581" alt="v2" src="https://github.com/bhratsharmaa/1mg-analysis-project/assets/132134997/0da87599-eb4f-4f67-9b3b-d6939dfe3ab6">






#### Distrbitution of customer ratings 







<img width="805" alt="v3" src="https://github.com/bhratsharmaa/1mg-analysis-project/assets/132134997/9ab9fd00-0037-4882-b817-80134d71924c">






#### Top 10 Highest rated brands  









<img width="553" alt="v4" src="https://github.com/bhratsharmaa/1mg-analysis-project/assets/132134997/438bfca1-f4f5-42e6-9429-f3ec11c06803">








#### Key incredients in top 5 rated brands 








<img width="531" alt="v5" src="https://github.com/bhratsharmaa/1mg-analysis-project/assets/132134997/c9babcf4-f426-4d23-bd78-b860b2452abf">







#### Top 5 most expensive Key benefit Areas 






<img width="529" alt="v6" src="https://github.com/bhratsharmaa/1mg-analysis-project/assets/132134997/197850ca-1282-4fe7-ba8a-cc73581f2230">








#### Bottom 5 Key Benefits Acc. To   Total Prodcuts Ordered  




 




<img width="462" alt="v7" src="https://github.com/bhratsharmaa/1mg-analysis-project/assets/132134997/69efdb62-3965-4219-9123-cacbb0682fbd">








## Dashboard 








<img width="603" alt="v8" src="https://github.com/bhratsharmaa/1mg-analysis-project/assets/132134997/4dca3c92-b7c9-491c-8307-1202b0a3bbea">











## 🛠 Tools used


BeautifullSoup,Excel,Python
## Suggestions:
1) Capitalize on the popularity of SBL Pvt Ltd. by prominently featuring its products and offering special promotions to attract more customers and boost sales.

2) Consider reviewing and optimizing the pricing strategy, especially for products with lower ratings, to improve customer satisfaction and potentially increase average ratings.

3) Analyze the distribution of customer ratings to identify areas for improvement, focusing on enhancing products with lower ratings to enhance overall customer satisfaction.


4) Leverage the high rating of Similia Homeo Laboratory to build trust with customers. Highlight this brand's positive reviews in marketing materials and on the website.

5) Promote Phenolphthalein 1x as it was the most popular product among the top 5 highest-rated brands. Consider bundling it with other products to cross-promote and increase sales.

6) Evaluate the pricing strategy for products in the "Hair" key benefit area to ensure it aligns with market expectations while maintaining product quality.

7) Diversify the product range in the "Hair" section to cater to a broader audience. Introduce budget-friendly options to capture a wider customer base.

## Challenges faced:
1) Navigating and scraping data from dynamically changing webpages on the 1mg website, where content could vary across pages.

2) Identifying the most suitable chart types that not only effectively convey insights but are also visually appealing.

3)  Creating an interactive dashboard that seamlessly integrates data, insights, and user-friendly functionality.

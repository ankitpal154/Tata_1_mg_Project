# Tata-1Mg-Homeopathic-medicine-Analysis

This project involves analyzing data related to medicine products, including their benefits, pricing, brands, ratings, and ingredients. The goal is to generate insights that can be used to create an interactive dashboard for analyzing the cost of opening a homeopathic medicine store and selecting the best medicine based on benefit area. 


##   **User's Manual**

| Files/Folder| Description |
| ------------- | ------------- |
| **Excel file** | This file provides the cleaned data after data cleaning.  |
| **Python File** | This contains the .ipynb file related to the web scrapping part.  |
| **Other Excel file** | This will provide the raw files after web scraping |
| **Project Prestation** | This file have the dashboards and insights of the project. |

##   Analysis

- Number of medicine available of different benefit area.
- Price range of medicine for each benefit area.
- Brand specialization(Key Benefits) of each area.
- Average price, min price , max price and number of products for each brand.
- Average number of rating for each brand in their specialization products where  the number of rating is not NULL.
- Maximum number of times ingredient used in each benefit area.
- Average cost for ingredients.
- Most used ingredient
- Which brand has most greater than 4 point review medicine?



##  Tools and Languages used

- Scraped the data with the help of Python BeautifulSoup librariy.
- Used Pandas for the data framing part.
- Analysis was done with the help of Pandas and Excel.
- Insights were generated from the above analysis.
- Excel is used for dashboard and data visualization.

# Dashboard
![1mg dashboard](https://github.com/ankitpal154/Capstone_project/assets/139064260/e9d479ef-7ca7-4924-a389-0008cc786d79)



# Insights

- Availability of  medicines are higher in skin followed by eye and digestion field.

- Lowest number of medicines in tooth, cardiac and diabetes field.


![Medicine availability analysis](https://github.com/ankitpal154/Capstone_project/assets/139064260/0a592d2d-c71e-479d-82fd-4e6b552b44ee)


- Highest maximum price of medicine is present in dental category.

- lowest minimum price of medicine is present in dental category.

![Price analysis](https://github.com/ankitpal154/Capstone_project/assets/139064260/aaa5f33b-2b1c-4553-9658-75c3c1064a86)



- For Dental products, the most used brand is Bakson's Homeopathy having average rating of 2.9


![Brand analysis](https://github.com/ankitpal154/Capstone_project/assets/139064260/d5f9a4f3-c7d2-4658-8bd9-4459ffaa5ade)




- For Diabetes products, the most used brand is Dr Reckeweg & Co having average rating of 4.7.

- Medicines of SBL Pvt Ltd have the highest percentage of products having rating greater than 4.


![most greater 4 point review](https://github.com/ankitpal154/Capstone_project/assets/139064260/ff8a85f1-2a46-4351-808a-a820497eebaa)

![most used ingredients and avg price](https://github.com/ankitpal154/Capstone_project/assets/139064260/3b80bcaa-54e2-4dfd-9a7c-9fbdd909a33f)
# Conclusion

- Market capture of SBL Pvt Ltd is comparatively better than others.
- Better Scope in the Dental Category Because Competition in that Category is comparitively low.
- Approximately 9-10 lakh Indian Rupees is required to open a homeopathic medicine store in a Tier 2 city.
 
![Guestimate](https://github.com/ankitpal154/Capstone_project/assets/139064260/22524af8-bb53-48ef-940a-4455a0211aa0)
# Challenges Faced
- **Website Ban**: Faced repeated bans on the 1Mg official website during data scraping attempts.
- **Google Colab Solution**: Resolved the issue by migrating scraping operations to Google Colab.
- **Extended Scraping Time**: Extracting details of each medicine took more time than anticipated.
- **Duplicate Data Issue**: Encountered delays due to duplicate data in the scraping process.
- **Learning Efficiency**: Gained insights into optimizing scraping methods for speed and accuracy.

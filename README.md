# Shoes Galore Project
In this project, our team is working on analyzing certain trends of women's shoes. In the dataset we are using, which can be found in clean_data.csv from https://data.world/datafiniti/womens-shoe-prices, we have data that incorporates different brands of women's shoes and the kinds of shoes that are produced from those brands. We look to answer certain questions that can shine light on popular shoes brand and shoe types for women that can be found from certain retailers such as Amazon and Wal-Mart.

## Introduction
You wear shoes. He wears shoes. She wears lots of shoes. Shoe sales are paramount to retail industry sales as they are quite literally the base of any good retailer’s foundation. Shoes are the completer to any outfit so as you could imagine there are many different pairs, colors, and types of shoes. For our first project our team looked at a 10,000-row data set that contained information about women’s shoes – color, size, category, several others key pieces from Amazon and Walmart both in-store and online. We decided that to best look at the data we would answer the following questions...

## Analysis Questions
1. What are the most popular shoe types made for women (boot, sandal, heels, etc.)?
2. Out of the shoes being produced, what are the top brands that are produced?
3. What is the average price point of the top brands?
4. What are the top colors and the average price points of those colors? 
5. Does shoe type affect pricing?
6. Does shoe size affect pricing?

## Visualizations and Observations
### Question 1: What is the impact of women on shoes and what kinds of shoes are being produced? What category of shoe is most widely made for women? Boot, sandal, heels, etc.

![image](https://user-images.githubusercontent.com/88349512/139356835-937d0e39-32ce-4905-b8bf-c5553268830b.png)

* For all 10,000 shoes, we grouped each shoe into a category of boots, sandals, flats, athletic, heels, and other. Out of those shoes, the most popular category of shoe made for women are boots with a total of 3,393 shoes which accounted for 33.9% of all shoes within the dataset.
* In comparison, the least popular category of shoes are heels with a total of 1,017 shoes which accounted for 10.2% of all shoes in this dataset.
* We can see that the “other” category which makes up 20.3%, contains shoes that don’t necessarily fit into any of the chosen categories which can suggest that women tend to like a variety of shoe types which may prompt retailers to produce a variety of shoe types.


### Question 2: Out of the shoes being produced, what are the top brands that are produced?

![image](https://user-images.githubusercontent.com/88349512/139354764-267ff129-1916-4fe7-9d7d-d113beffbd14.png)

* The top 10 brands make up 40.8% of all womens shoes in this data set.
* Brinley Co. makes up 24.7% of the top brand of top ten brands of shoes. The bottom 4 brands combined, Aerosoles, L'Artiste by Spring Step, Drew, and Easy Street, make up only 20.1%
* The top three brands, Brinley Co., Propet, and SAS, make up 51.5% of all shoes in this data set.


### Question 3: What is the average price point of the top brands?

![image](https://user-images.githubusercontent.com/88349512/139354788-9773d987-fc25-4623-a280-35ce7c4cfbc3.png)

* The brands Soda and Brinley Co. are the lowest average price at $32.76 and $35.86, respectively.
* SAS has an average price of $141.61 and Drew has an average price of $140.20 making these the highest average brands.
* The company could earn an extra $1,127.25 a month ($13,527 annually) if they discounted SAS and Drew brand shoes 20% and gained 5 more shoe purchases a month per brand.


### Question 4: What are the top colors and the average price points of those colors?

**Total Number of Shoes Produced per Top Shoe Color**

![image](https://user-images.githubusercontent.com/88349512/139357223-06736f93-59fc-4297-83ab-31fd35258190.png)

* Black shoes represent the majority of shoes produced making up 45.71% of the number of shoes produced amongst the other colors in the top ten shoe color category with a total of 2561 shoes produced.
* White shoes came in second making up 15.60% of the number of shoes produced amongst the other colors in the top ten shoe color category with a total of 874 shoes produced.
* Out of the top ten colors, tan shoes came in last, making up 3.93% with a total of 220 shoes produced.


**Average Price Point per Top Shoe Color**

![image](https://user-images.githubusercontent.com/88349512/139357252-d44e6571-94cf-45fb-956c-4293c8877b82.png)

* White shoes typically cost the most having an average price point of $92.96. 
* Black shoes came in second having an average price point of $74.18. 
* Out of the top ten colors, grey shoes have the lowest average price point coming in at $47.90. 


### Question 5: Does shoe type affect pricing?

![image](https://user-images.githubusercontent.com/88349512/139357281-ec86a34c-63c6-4c7a-b13e-15734337f9d9.png)

* Median shoe prices run from $33 for flats to $64 for shoes in the ‘other’ category.
* The ‘other’ category may reflect higher prices due to more expensive brands having more creative names for their shoes that are not caught by our filters.
* Several outliers exist for shoes costing over $100 ($117 is the top whisker for flats).
* 18 shoes with prices over $500 were removed from the data before analysis.


### Question 6: Does shoe size affect pricing?

![image](https://user-images.githubusercontent.com/88349512/139357306-a9622d24-2f2d-4c49-a0b3-9199bc89a857.png)

* There is little correlation between shoe prices and sizes (the r-value is: 0.06).
* 18 shoes with prices over $500 were removed from the data before analysis.
* Sizes outside the range 4 to 12 were not analyzed.
* Half sizes were rounded down to whole numbers.


## Conclusion
*What conclusions can we draw from the data about shoes for sale from Amazon and Walmart?*

* Brinley Co. is the most popular brand and makes up 10.1% of all shoes.
* Most popular shoe category are boots.
* Black shoes represent the majority of shoes produced.
* White shoes typically cost the most.
* The top brand with the lowest average price is Soda while the top brand with the highest average price is SAS.

*What did we learn from this project? Are there limitations we should be aware of?*

As you start to analyze the data, you begin to ask more questions upon discovering conclusions as you go on. We revamped some of the questions and what we were looking for based upon the strengths and limitations of the data.

Even though a data has limitations that can be a telling truth when making conclusions. We were limited in some of the things we wanted to know about the data – our group kept going back to the idea of we really wish that we had the sales information of the shoe data that we were looking at. Having that information we would have been able to make several more conclusions beyond what we had listed.

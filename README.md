# Wine Reviews Data Analysis 
____________________________________________________________

By: Danielle Anderson, Eric Simon, Omar Solis, and Tali Tesar

This project consists of an analysis of [wine data](https://www.kaggle.com/datasets/zynicide/wine-reviews) that was scrapped from [WineEnthusiast](https://www.winemag.com/?s=&drink_type=wine) by the user [ZACKTHOUTT](https://www.kaggle.com/zynicide) on kaggle. The wine data consisted of over 130,000 different wines, including a review and score from a professional sommelier, and our analysis centers around the questions:


         1. What wine has the best value (highest rating for lowest price)?
         2. What countries produce the highest quality and highest price wines?
         3. What are the different ways in which wine can be described and how do these descriptions affect price?
         4. What different names of fruits are used most commonly in reviews in general and by country?

### About the Wine Data 

The data consists of 10 fields:

- *Points*: the number of points WineEnthusiast rated the wine on a scale of 1-100 (reviews that are posted only scored >=80)
- *Title*: the title of the wine review, which often contains the vintage if you're interested in extracting that feature
- *Variety*: the type of grapes used to make the wine (ie Pinot Noir)
- *Description*: a few sentences from a sommelier describing the wine's taste, smell, look, feel, etc.
- *Country*: the country that the wine is from
- *Province*: the province or state that the wine is from
- *Region 1*: the wine growing area in a province or state (ie Napa)
- *Region 2*: sometimes there are more specific regions specified within a wine growing area (ie Rutherford inside the Napa Valley), but this value can sometimes be blank
- *Winery*: the winery that made the wine
- *Designation*: the vineyard within the winery where the grapes that made the wine are from
- *Price*: the cost for a bottle of the wine 
- *Taster Name*: name of the person who tasted and reviewed the wine
- *Taster Twitter Handle*: Twitter handle for the person who tasted ane reviewed the wine



### Wine Analysis Conclusion
___________________________________________________________

- Great wine is possible to purchase for as little as $4
- Spending over $43 on wine is generally not worth it as scoring in the $26 to $42 range is comparable 
- Top 5 highest scored countries are England(91.22), India(90.22), Austria(90.20), Germany(89.84), and Canada(89.37).
- Top 5 most expensive countries Switzerland($85.29), England($51.68), Germany($42.45), Italy($41.61), and France($41.19)
- There was no significant difference in flavor profile value or body scale value for different price levels, and the wines with extreme flavors or body are generally the cheapest.
- *Recommended Sources of Flavor*: Berry - Isreal, Stone Fruits - Bulgaria, Citris - German, Fruit variety - Hungary

### Key Visuals and Tables
___________________________________________________________

*Best Value Wines by Price Point*

![image](https://github.com/oas95/project1-wine-reviews/blob/main/Pywine/Output/Best_value_wines2.png)

*Top 5 Highest Rated and most Expensive Wines by Country*

![image](https://github.com/oas95/project1-wine-reviews/blob/main/Pywine/Output/Top5%20Countries%20on%20score.png)![image](https://github.com/oas95/project1-wine-reviews/blob/main/Pywine/Output/top_5_most_expensive_countries.png)

*Average Score vs Price by Country Scatterplot*

![image](https://github.com/oas95/project1-wine-reviews/blob/main/Pywine/Output/country_scorevsprice.png)

*Price vs Flavor Profile & Price vs Body Profile*

![image](https://github.com/oas95/project1-wine-reviews/blob/main/Pywine/Output/Price_vs_flavor.png)![image](https://github.com/oas95/project1-wine-reviews/blob/main/Pywine/Output/pricevsbody.png)

*Pie Chart for Top Fruitiest Wines by Country*

![image](https://github.com/oas95/project1-wine-reviews/blob/main/Pywine/Output/Bulgaria_top_fruits.png)![image](https://github.com/oas95/project1-wine-reviews/blob/main/Pywine/Output/Germany_top_fruits.png)![image](https://github.com/oas95/project1-wine-reviews/blob/main/Pywine/Output/Israel_top_fruits.png)

### Sources
____________________________________________________________
Data Source: https://www.kaggle.com/datasets/zynicide/wine-reviews

Wine Word Bank Source: https://winefolly.com/deep-dive/wine-tasting-terms-to-use/

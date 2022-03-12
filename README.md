# <h1> Sales Prediction Project </h1>
<h2> Project Overview </h2>
<p> The Sales Prediction Project uses past data from multiple retail outlets to predict future sales. Using multiple Python libraries, we have; cleaned, explored, and pre-processed data to prepare the data for machine learning. Using 2 different machine learning models, we were able to fine-tune our ML models to deduct the best implementation method for the project. </p>

<h2> Data Information </h2>
<p> See original data source here: https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/ </p>
<p> The data used in this project can be found here: https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view?usp=sharing </p>
<h1>Data Dictionary</h1>

| Variable Name             | Description                                                                                         |
|---------------------------|-----------------------------------------------------------------------------------------------------|
| Item_Identifier           | Unique product ID                                                                                   |
| Item_Weight               | Weight of product                                                                                   |
| Item_Fat_Content          | Whether the product is low fat or regular                                                           |
| Item_Visibility           | The percentage of total display area of all products in a store allocated to the particular product |
| Item_Type                 | The category to which the product belongs                                                           |
| Item_MRP                  | Maximum Retail Price (list price) of the product                                                    |
| Outlet_Identifier         | Unique store ID                                                                                     |
| Outlet_Establishment_Year | The year in which store was established                                                             |
| Outlet_Size               | The size of the store in terms of ground area covered                                               |
| Outlet_Location_Type      | The type of area in which the store is located                                                      |
| Outlet_Type               | Whether the outlet is a grocery store or some sort of supermarket                                   |
| Item_Outlet_Sales         | Sales of the product in the particular store. This is the target variable to be predicted.          |

Created Using https://www.tablesgenerator.com/markdown_tables

<h2> Understanding the Data </h2>
<p> The Data does not come ready for processing and must be cleaned/manipulated to work with most Machine Learning models. When using the data it is important to understand what aspects of the data may be related. There is more in-depth information inside of the project about this, however on this heatmap you can see the similarities between certain properties. </p>

![Heat Map](https://raw.githubusercontent.com/jacobmlloyd/sales-prediction/main/Visuals/heatmap.png)

<p> Since the goal of the project is to predict future sales information, we should see what properties the data has that actually affects the sales. We can deduct from the heatmap that the Item_MRP has a rather high correlation to Outlet_Sales. When analyzed further we can see that there is a direct positive correlation.</p>

![Heat Map](https://raw.githubusercontent.com/jacobmlloyd/sales-prediction/main/Visuals/price_sales_plot.png)

<h2> Results and Recommendations for Implementation </h2>
<p> While we tested 2 machine learning models, and fined tuned one, I would recommend testing other machine learning algorithms to see if any better-fit our data. Based on the two models used, Linear Regression and Decision Tree Regression, I would recommend a fine-tuned Decision Tree Model. This model had the most accurate predictions out of the two, and is tailored to the data. For a more in-depth explanation please review the video in https://github.com/jacobmlloyd/sales-prediction/blob/main/Video/</p>

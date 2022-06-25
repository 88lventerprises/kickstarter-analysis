
## **Overview of Project**
In this analysis our team is assisting an up-and-coming play write, Louise, review her crowdfunding campaign for her play, Fever. She had hesitancy in jumping into her first fund raising campaign and is relying on our skillset to make more informed decisions and create strategies that support her goals through a provided Kickstarter campaign data set. 

From our previous analysis we uncovered Fever came close to reaching its fundraising goal, and Louise is interested in extracting a comparative analysis of launch dates and funding goals from previous campaigns. Our team will use excel visualization tools, subcategory analysis, pivot chart analysis, filtering, statistical analysis, and coding to generate a digestible written report to better understand Louise's performance in comparison to others Kickstarter in her niche.

### *Purpose*

The purpose of this analysis is to provide granular insight on a subset of data for our playwright. With our analysis Louise will compare and implement more instructed agenda in accomplishing her Kickstarter goal. The question that is most pertinent for Louise is, how did different campaigns fare in relation to their launch dates and their funding goals? With this we will be able to draw conclusions from the data set based on the following criterion,  outcome vs. launch date analysis and  outcome vs goals. Ultimately this will refine our technical analysis skillset as we execute visualization strategy and written analysis.

## Analysis and Challenges

The data set consisted of over 4,000 rows of Kickstarter data points across multiple international subgroups. Our team focused primarily on theater and plays to refine the data set and identify trends that best suit our playwright’s goals.

### *Analysis of Outcomes Based on Launch Date*
This chart will provide visualization of the relationship between outcomes and launch month over the course of 8 years

![](https://raw.githubusercontent.com/88lventerprises/kickstarter-analysis/a8093f7ddeb2cf01459caee562f41ea032e6286b/Resources/Theater_Outcomes_vs_Launch.png)

### *Analysis of Outcomes Based on Goals*

This chart will provide dollar amount ranges for plays based on their goal amount and populate the number of Successful, Failed and Canceled Kickstarter campaigns

![](https://raw.githubusercontent.com/88lventerprises/kickstarter-analysis/a8093f7ddeb2cf01459caee562f41ea032e6286b/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

One of the primary challenges I encountered in the exercise was the ability to translate our objectives into an equation "X" input and "Y” output. Each scenario Louise presented required quantitative analysis to answer that question “Y”, whilst "X" acted as the formula to extract the information from the data subset. Assuming formulas account for filtering in our primary data set (COUNTIF), I hit a huge roadblock. Although I was able to draw an analysis from the data set it was not tailored to the plays within the Kickstarter program. This led me to a bit of confusion, but through self-study and leveraging my network, I was able to uncover the purpose of the formula (COUNTIF) and the criterion on which the outcomes are based. This is the data filtration. Immediately, I noticed that understanding our audience’s question is just as important as having the tools for the answer. This analysis helped me realize how efficient data can be at telling stories, leveraging visualization, and removing “gut feeling” decision making.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The first conclusion we can draw is over the course of 2009-2017 May June and July are the optimal months to release Theater related Kickstarter.
The second conclusion we can draw from the data set is over the same 8-year span, 61% of Theater related Kickstarter were successful.

- What can you conclude about the Outcomes based on Goals?

We can conclude that plays between $1000-$4999 have an average percentage success rate of 74.5%

- What are some limitations of this dataset?

Some limitations of the data set are primarily outliers that skew our ability analyze that data effectively as it has adverse outcomes of our mean value. An additional limitation of the data set, after placing the Kickstarter campaigns into subgroups, is the finite amount of data points. Also, genre and other demographics that may pinpoint outcome is not represented in our dataset, which can misinform our playwright. Variables are vast in the subject matter of Theatre and plays, more insight and target would have added more concrete evidence of the success, failure, or cancelation of a play.


Other types of charts we could have used are stacked or clustered columns showing us a side-by-side barred representation on outcomes based on goals. This would've clearly defined which goals were most dominant 

![](https://raw.githubusercontent.com/88lventerprises/kickstarter-analysis/a8093f7ddeb2cf01459caee562f41ea032e6286b/Resources/Stacked_Column.png)

![](https://raw.githubusercontent.com/88lventerprises/kickstarter-analysis/a8093f7ddeb2cf01459caee562f41ea032e6286b/Resources/Clustered_Column.png)
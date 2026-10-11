# Customer-Segmentation-Analysis
Consumer insight analysis of 2,208 grocery customers, identifying which segments to target with marketing. SQL + Tableau.

The Question

This project aimed to find out which customers a grocery retailer should focus its marketing on. This matters because the retailer can look at what their marketing budget is focused on and where the money makers are and adapt the budget to get more revenue from the same budget.

The Data

I used the Customer Personality Analysis dataset from Kaggle, which contains 2240 customers of a food and grocery retailer. After cleaning, 2208 remained and was cleaned by removing impossible ages by removing 3 customers (1893, 1899 and 1900). Also, I removed some incomes (24 were blank and 1 was 666,666). 4 more were removed due to odd marital statuses like “absurd” and “YOLO”.

Methods

I split customers into higher and lower income by finding where the median income was (51371); they were lower if it was less than that and higher if it was more than or equal to that. Customers with any children or teenagers at home were counted as having kids. This was all done in Excel. The data was then imported into Tableau, where I made the graphs.

Findings

Consumers with a higher income and without kids spent more and responded more to campaigns. I hypothesise that they have higher disposable income for shopping and more time to spend it. In terms of campaigns, they again have more time to pay attention to these campaigns and take action, whereas those with kids may not even notice the campaigns, and if they did, probably don’t have the time to spend on extra things. However, this is a hypothesis that the data alone cannot prove; research would have to be done, such as a survey on how much time these groups spend shopping.

Higher-income families with kids spent a lot (812 on average) but responded least to campaigns (9%). This suggests that income isn’t the barrier for these families; it is likely to be other factors, such as time or attention. As seen in the charts, having kids seems to matter more for campaign response than income does. Habitual purchasing has a strong effect on what brands people tend to buy, as they tend to stick to familiar ones, which may make them less likely to switch to a promoted brand.

Limitations

A limitation is that it’s only one retailer, and we cannot infer cause from correlation alone. Also, income and family status most likely overlap with age.

Recommendations 

In terms of the group that spends the most (higher income, no kids), the retailer needs to keep these customers shopping at their company. To do this, they could give this group early access to products or promote more premium products that might suit them better. They should spend a larger share of their campaign budget targeting this group too.

For families, if the barrier is time, the retailer should try personalised app offers or meal deals/ bundles that would free up time in both buying dinners and cooking them. 

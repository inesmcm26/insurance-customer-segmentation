# InsuranceCustomerSegmentation


## General Context
Finding new customers is vital in every industry. The process for finding new customers begins by learning as much as possible from the existing customers. Understanding current customers allow organizations to identify groups of customers that have different product interests, different market participation, or different response to marketing efforts. With this, we will be able not only to serve better our customers, but also to improve the targeting of prospective customers.
<br>
Market segmentation, the process of identifying customers’ groups, makes use of geographic, demo-graphic, psychographic, and behavioral characteristics of customers. By understanding the differences between the different segments, organizations can make better strategic choices about opportunities, product definition, positioning, promotions, pricing, and target marketing.

## Business Situation
A2Z Insurance (A2Z) is a portuguese long standing insurance company that serves a wide array of insurance services: Motor, Household, Health, Life and Work Compensation. Although A2Z primarily serves portuguese customers, a significant portion of their customer acquisition comes from their web site. Customers can sign up to A2Z services through their branches, by telephone, or on the web site.
<br>
In 2016, A2Z became one of the largest insurers in Portugal. However, the lack of a data driven culture in the company ultimately led to poorly maintained databases over the years. A2Z is trying to make better use of the database it has regarding its customers. So far, it has simply mass-marketed everything. All potential and existing customers get the same promotions, and there are no attempts to identify target markets for cross-selling opportunities. Now, A2Z wants start differentiating customers, and developing more focused programs.
<br>
A2Z provided an ABT (Analytic Based Table) with data regarding a sample of 10.290 Customers from its active database. These are customers that had at least one insurance service with the company at the time the dataset was extracted. The goal of the project is to segment the database and find the relevant clusters of customers. To do this, the customers were segmented using different perspectives and approaches, as well as by combining and analyzing the results.

## Goals
1. Explore the data and identify the variables that should be used to segment customers.
2. Identify customer segments and explain them
3. Suggest business applications for the findings and define general marketing approaches for each
cluster.

## Development process

All code was developed using python libraries such as sklearn, seaborn, matplotlib, plotly etc, and it can be found in the jupyter notebook. A report describing the whole process is also available. The dataset used is included in the files.

## Results

The final customer segmentation resulted in 4 clusters:
- Cluster 0 - Long-standing, wealthy: This cluster includes 1757 observations and is composed by older, wealthier clients who have been with the company for a longer time and generally spend an average and similar amount on Household, Health, Life, and Work. This cluster gatters a balanced number of clients with and without children, all being less literate. In order to encourage these customers to continue doing business with the company, it might be a good strategy to offer them loyalty rewards and develop marketing campaigns that highlight the value and prestige of being a long-standing customer.
- Cluster 1 - Young, profitable: This cluster includes 1507 observations and is made up of younger, less affluent clients who spend a lot on Household, Life, and Work insurance and the least on Motor. They are the most recent and profitable clients, who have low levels of education and a majority has children. Given their age, these clients may be more likely to engage with the company on social media, so investing in social media marketing campaigns to reach this group and showcase the products and services might be a good strategy.
- Cluster 2 - Risky: This is the largest cluster counting 3713 observations. It includes middle-aged clients with an average salary who have the lowest ClaimsRate but also the lowest total spending on premiums. They spend a lot on Motor but very little on the other types of insurance and their contracts result in higher reversals than the other clusters. This cluster is made up of highly educated clients, so the company may consider offering educational resources such as webinars or workshops to help them make informed decisions about their insurance needs, perhaps, making them diversify their insurance investments.
- Cluster 3 - Average: This cluster includes 3142 observations and is composed of average clients who are middle-aged and earn an average salary. These clients are the highest spenders on Health insurance and have ordinary spending on the other types. It includes customers from all education levels and has a relatively balanced number of people with and without children. This cluster is composed of clients with diverse needs, so the company may consider offering special packages that allow them to purchase multiple services at once.


### Clusters profilling

Numerical variables
![Numerical Variables](/images/lineplot.png)
Categorical variables
![Categorical Variables](/images/histplot.png)

### Clusters visualization using t-SNE
![t-SNE](/images/tsne.png)

### Summarizing Bubble Chart
![Bubble Chart](/images/bubble.png)

### Clusters silhouettes
![Clusters silhouettes](/images/silhouettes.png)





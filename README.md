# Ecommerce Customer Churn Exploratory Data Analysis

This project explores churn behavior in an ecommerce dataset of 8,000 customers between 2011 and 2026.
The goal is to uncover patterns that influence whether customers stay active or leave.

- 📂 Dataset: [customers.csv](https://github.com/DataStudioHQ/ecommerce-customer-churn/blob/main/customers.csv)  
- 📓 Notebook: [ecommerce_customers_EDA.ipynb](https://github.com/DataStudioHQ/ecommerce-customer-churn/blob/main/ecommerce_customers_EDA.ipynb)
## Exploratory Data Analysis Workflow



 ### Age Distribution of Customers.

![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreiavrynzqxhrqlejp5yhqupppd4gwymznlj76kn7qkmb3bq4jlpa7i)

Most customers are age 18 to 40, with the range of 18 to 25 group (1,477) the largest. The numbers of customers decline after age  45. Younger users dominate. Retention should focus on under-40s.

### Gender of Customers

![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreicq5c7kvc2hddxketfkgo2h7uj2yxd5fpbjudfiaphv75eoxjbn4y)

Gender split is nearly equal: 48.7% female, 48.3% male, 3% other. Gender balance means churn is driven more by behaviour than demographics.

### Distribution by Country

![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreiahxr4cgeb5ogrxycs4gzpzg6icpgu3jg2hreak4bkvwsl3dosrpu)
Top markets: US (31.36%), UK (10%), India (8.89%), Germany (7.96%).

 Global reach, but heavily concentrated in the US. Growth potential abroad.

#### Membership Tier Distribution
![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreieapbx26lohnncsnddw5lxn2q63bfegybgo3jbq547i7d4gfkfttm)


Most customers are Free tier (4,443), followed by Silver tier (1,736), Gold tier (1,177), Platinum tier (644).

Strong acquisition, but conversion to paid tiers is limited.


#### Total Spend Distribution
![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreiagymktbqeyoj5vyhljs37pu2n6xtfeq3ab4uclkenjuh547l32ha)

Most customers spend between $400 and $3,000, with fewer spending at the extremes. The bell-shaped curve peaks around moderate spending levels, where customer count reaches about 500.


![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreie2gjnlrlsl3gqtaxdkym4gxm4k7c66pfstaof3dtrhgkdwvbtq2a)

The Spend Distribution by Range charts compare customer spending across four tiers:

- 0–1k USD: Most customers fall here, with spending concentrated at lower levels.

- 1k–5k USD: Fewer customers, showing a gradual decline as spend increases.

- 5k–20k USD: Sparse distribution, representing mid- to high-value customers.

- 20k–60k USD: Very few customers, indicating a small elite spending group.

Most customers are mid-range spenders, while high-value customers form a small but crucial group for targeted retention and premium-tier strategies.

#### Distribution of Days Since Last Purchase

![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreichrhjtqs2v7cbb7qrqkwwifvkwtg46zbqb3yhoccwnruvjap6jmq)

Activity is highest among recent buyers, dropping sharply over time. Reactivation campaigns are key for long-inactive customers.

### Product Preference Distribution

![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreidliacqmz46woz6yoqrsbb6wx72cbnhjp5v37iofpkarz274uqqxa)

Tech and fashion dominate. Weaker categories need targeted promotions, indicating strong engagement in high-demand categories. Lower performing segments could benefit from targeted promotions or cross-category recommendations.


![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreigepvemly73a6la4d63eabbj54msnnxx5wxdnyna4be5w3wli4rou)

Customers preferred traditional payment methods with credit and debit cards dominating 60% of the distribution


### Customer Acquisition
![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreibl6wegv3ecrvlmqprfhrn6i44tzyzdjcrx5ommmczqs2hkf3dgty)

This reveals a clear hierarchy in how users discover the platform. Organic search (2,194 customers) is the dominant acquisition source, underscoring the effectiveness of SEO and brand visibility.

Social media (1,758) and email campaigns (1,494) follow closely, reflecting strong engagement through content and direct communication.

Paid ads (1,255) contribute meaningfully but at a higher cost per acquisition, while direct visits (826) and referrals (473) lag behind suggesting limited word-of-mouth traction and brand loyalty-driven traffic.

### Customer Churn

![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreicj2d5heaiufxofirf2tbpjueee2i7wzltgy6uocc3otaoaomfo3y)

Out of 8,000 customers, 7,285 (91.1%) remain active, while 715 (8.9%) have churned. This indicates a strong retention rate, suggesting that the platform’s engagement and value proposition are effective for most users.

![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreihfyxuldn5ywxh24dx6htwkwncik2xuhp57rskz3q2zadkbpszkwe)

### Churn vs Membership Tier

| Membership Tier | Active Customers | Churned Customers | Total Customers | Churn % |
| --- | --- | --- | --- | --- |
| Free | 4,020 | 423 | 4,443 | **9.5%** |
| Silver | 1,613 | 123 | 1,736 | **7.1%** |
| Gold | 1,061 | 116 | 1,177 | **9.8%** |
| Platinum | 591 | 53 | 644 | **8.2%** |

- The **Free tier** has the largest customer base and the highest churn count, while **Platinum** members show the lowest churn.


- The Free tier has the largest churn count (423), but its churn rate is lower than Gold.

- Gold tier shows the highest churn percentage (9.8%), even though it’s a paid tier.

- Silver tier performs best among paid tiers with the lowest churn rate (7.1%).

- Platinum tier has the smallest base and lowest churn count, with a moderate churn rate (8.2%).

### Global Churn vs Preferred Category  
![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafybeiaavhn3y6jxa2g3q7wnjcn6b2s4mv4r4ftt7glct7rpvyyajocbk4)





### Churn vs Preferred Category by Gender
![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreicoiviujd2mvsdluomp2rqxa3nnngwvw7y3rvx7kq2qi4l7uq3r7a)


 
Across all Countries and gender groups, **Clothing & Apparel** and **electronics** drives the highest retention.

### 🔍 Churn vs Acquisition Channel

![App Screenshot](https://violet-raw-squirrel-412.mypinata.cloud/ipfs/bafkreigcmqndiltjhkaogl3ykuskqlqgz7yfxnaqlqzfmjsacfewga6t5u)

| Acquisition Channel | Active Customers | Churned Customers | Key Insight |
|----------------------|------------------|-------------------|--------------|
| Organic Search       | 2,016            | 178               | Highest acquisition and retention. Strong SEO and brand visibility. |
| Social Media         | 1,595            | 163               | High engagement but moderate churn. Improve post-acquisition retention. |
| Email Campaign       | 1,359            | 135               | Balanced performance. Effective for nurturing existing leads. |
| Paid Ad              | 1,142            | 113               | Steady acquisition. Optimize targeting to reduce churn. |
| Direct               | 747              | 79                | Smaller but loyal base. Strong brand recognition. |
| Referral             | 426              | 47                | Lowest churn rate. Trust-driven acquisition channel. |
  
**Organic search** channel deliver the most sustainable growth, while **social media** and **paid ads** show room for improvement in retention.

 **Refferal** shows the higest churn rate


### Correlation with Churn


| Variable                | Correlation with Churn | Relationship Type | Key Insight |
|--------------------------|------------------------|-------------------|-------------|
| Days Since Last Purchase | **0.183**              | Moderate Positive | Longer inactivity strongly increases churn risk. |
| Newsletter Subscribed    | 0.013                  | Very Weak Positive | Minimal effect. Subscribers slightly more likely to churn in this dataset. |
| Age                      | 0.000                  | None              | Age has no meaningful impact on churn. |
| Wishlist Items           | -0.001                 | None              | Wishlist activity does not predict churn. |
| Avg Order Value (USD)    | -0.004                 | Very Weak Negative | Higher average order value slightly reduces churn. |
| Avg Review Score         | -0.021                 | Very Weak Negative | Better reviews weakly correlate with retention. |
| Total Spend (USD)        | -0.047                 | Weak Negative     | Higher spend modestly reduces churn likelihood. |
| Returns Made             | -0.056                 | Weak Negative     | More returns weakly reduce churn possibly due to continued engagement. |
| Reviews Given            | -0.080                 | Weak Negative     | Active reviewers are less likely to churn. |
| Total Orders             | **-0.091**             | Weak Negative     | More orders correlate with stronger retention. |

 
- The strongest churn driver is **days since last purchase**, confirming that **recency** is the most predictive factor.  
- **Total orders** and **total spend** show weak but meaningful negative correlations, suggesting that loyal, high-value customers are less likely to churn.  
- Engagement signals like **reviews given** and **returns made** also weakly reduce churn, showing that activity, even returns, keeps customers connected.

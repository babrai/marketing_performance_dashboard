# Marketing Performance Analysis

## Task
Build a Tableau dashboard to help the marketing team evaluate the performance of paid traffic from different sources.  
Analyze traffic performance, provide insights, and suggest hypotheses for optimization.

## Data
**Table `campaign_performance`:**
- `date` — campaign activity date  
- `media_source` — traffic source  
- `campaign_id` — campaign ID  
- `spend` — ad spend (USD)  
- `impressions` — number of ad impressions  
- `clicks` — number of ad clicks  
- `installs` — number of app installs from the campaign  

**Table `user_revenue`:**
- `user_id` — unique user ID  
- `first_purchase_date` — date of first subscription purchase  
- `total_revenue` — actual revenue from this subscription  
- `campaign_id` — ID of the campaign the user came from  
- `forecasted_revenue_12m` — forecasted revenue for month 12 of the subscription lifecycle

## Dashboard
[🔗 View interactive Tableau dashboard](https://public.tableau.com/app/profile/varvara.iuchyk/viz/MarketingTrafficPerformance/MarketingPerformanceDashboard)


## Deliverables
- Interactive Tableau dashboard  
- Data files in `data/` folder

## Tools
- Tableau

## Key Insights
- **Apple Search Ads** shows higher ROI (**46%**) and forecasted ROI (**131%**) than **Facebook** (**22% / 56%**) with similar spend, while generating fewer installs.  
- Shifting budget toward **Apple Search Ads** may improve profitability, while **Facebook** can support broader reach.

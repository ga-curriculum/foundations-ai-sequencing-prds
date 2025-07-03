## Product Requirement Document (PRD): Customer Trends Dashboard

### Overview

The business needs a dashboard to help leadership and sales teams better understand customer retention and churn trends. The dashboard should show how these numbers change over time and allow for segmentation.

### Objectives

- Provide insight into customer churn and retention.
- Enable segmentation by product and region.
- Visualize trends to help inform business decisions.

### User Stories

- As a sales manager, I want to see churn rates so I can address customer loss.
- As an executive, I want to track retention and churn over time for key products.

### Data Sources

- Customer database
- Product usage logs

### Functional Requirements

- Calculate churn and retention.
- Allow segmentation/filtering by region and product.
- Visualize churn and retention over time.
- Dashboard should be accessible to the sales and executive teams.

### Acceptance Criteria

- Leadership can view “up-to-date” churn and retention trends by product/region.
- Dashboard is user-friendly and provides useful insights.

---

### **Open Questions / Potentially Missing Details**

1. What is the precise definition of “churn” and “retention” for this dashboard?
2. Over what time period should trends be calculated (monthly, quarterly, rolling, etc.)?
3. Are all customers included, or only paying/active ones?
4. How are products and regions defined—can customers belong to multiple?
5. What specific visualizations are expected?
6. How often should the dashboard update?
7. Are there any privacy or security restrictions on the data?
8. Are there any edge cases to handle (e.g., customers who churn and return)?
9. Who approves the dashboard as “useful” or “user-friendly”?

---

> **Instructor Note:**  
> This PRD is intentionally vague! Students should identify and articulate missing or unclear details before any code or prompt sequencing can begin.

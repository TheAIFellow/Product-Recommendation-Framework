# Product-Recommendation-Framework
Amazon uses recommendations as a targeted marketing tool in both email campaigns and on most of the pages of its website. Amazon will recommend many products from different categories based on what you are browsing and pull those products in front of you which you are likely to buy. Like the ‘frequently bought together’ option that comes at the bottom of the product page to lure you into buying the combo. This recommendation has one main goal: increase average order value i.e., to up-sell and cross-sell customers by providing product suggestions based on the items in their shopping cart or below products they’re currently looking at on-site.Amazon uses the browsing history of a user to always keep those products in the eye of the customer. It uses the ratings and reviews of customers to display the products with a greater average in the recommended and best selling option. Amazon wants to make you buy a package rather than one product. Say you bought a phone, it will then recommend you to buy a case or a screen protector. It will further use the recommendations from the engine to email and keep you engaged with the current trend of the product/ category.

## **WHAT ARE THE DIFFERENT TYPES OF RECOMMENDATIONS?**
---
### There are basically three important types of recommendation engines:
* Collaborative filtering
* Content-Based Filtering
* Hybrid Recommendation Systems

## **Feature Details**
* User_Id
* Product_Id 
* Review
* Ratings

### Steps:
* EDA/Feature analysis
* Data Preprocessing
* Machine Learning Models
* Model Evaluation

# **Conclusion**
---
From above we can conclude below points
* We got recall@5: 0.3847 and recall@10: 0.4759 for collaborative Model.
* We got recall@5: 0.83814 and recall@10: 0.8630 for content-based Model.
* As we can see We are getting better recall value for content-based model than collaborative model.
* So we can conclude that content-based model is optimal model for product recommendation.


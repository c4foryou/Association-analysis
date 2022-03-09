# Association analysis for a retail store (Apriori)

# **Summary**

**Introduction**: 

Association analysis is commonly conducted to make bundle products or recommend additional products to customers. As this analysis is important for marketing and customer recommendation, I found customer order data from a supermarket on Kaggle and used it for the analysis.

**Datasets**:

Product Data → Product data including product_id and product_name

Order Data → Order data including order_id and product_id.

**Language and libraries**: Python, Pandas, mlxtend

**Algorithm**: Apriori

**Evaluation**: Support, Lift, and Confidence

**Finding**: 

Pairs of vegetables, fruits, or a combination of a vegetable and fruit are showing high support and lift. These are high-turnover consumables and various items in these categories are bought for cooking, which is assumed as a reason for this finding. 

The below table contains 20 combinations ordered by lift

![ex_screenshot](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/cd4be1c7-0547-404b-ad38-bb03d0f6be94/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220309%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220309T182646Z&X-Amz-Expires=86400&X-Amz-Signature=a4656a2e72107b653ca1561b9807fc8c994adba663fcdf790348be329edbdc45&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject)

**Takeaways and future study topics**:

- Research on cross-category combination is needed
    
    The pairs of products that I found for this analysis can be considered as ‘common sense, and I guess marketers already know these are frequently selling together. Therefore, to provide more insight into the company’s marketing, further analysis for cross-category combination will be helpful to find an unexpected combination of products that shows good scores for evaluation metrics

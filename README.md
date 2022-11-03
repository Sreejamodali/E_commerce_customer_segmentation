# E_commerce_customer_segmentation

#PROBLEM STATEMENT
  As an e-commerce platform, it is very important to profile your customers, dividing your clientele base into groups based on their needs and expectations. Grouping will help us come up with dedicated marketing strategies and will aid us in recommending products to different user bases. In this project, we are interested in analyzing the content of an E-commerce database that lists purchases made by ∼4000 customers over a period of one year (1/12/2010 to 9/12/2011). Based on this analysis, we would like to develop models to group the 4000 customers into different buckets. Such a model must take into account the similarity between the products purchased between the users (i.e. a user might purchase 2 different products which are very similar to each other), the spending patterns of a user, their meta information, etc. 

Explaining the problem:-->
The client wants to know group of products that are commonly buying together, for example, when we buy shampoo along with shampoo we do buy conditioner and oil for hair 
as well as shower gel. Similarly, wants to segments products based up on customer preferences 
#steps to group products
#1. Grouping the Customers
  ->Using NLP on Description in dataset
  ->By grouping similar products using k_means clustering
  ->using k_means getting similar customers

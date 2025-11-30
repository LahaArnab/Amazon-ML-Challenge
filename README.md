# Amazon-ML-Challenge
Predict actual price of a product 
\\
**Problem Statement**
Smart Product Pricing Challenge
In e-commerce, determining the optimal price point for products is crucial for marketplace success and customer satisfaction. Your challenge is to develop an ML solution that analyzes product details and predict the price of the product. The relationship between product attributes and pricing is complex - with factors like brand, specifications, product quantity directly influence pricing. Your task is to build a model that can analyze these product details holistically and suggest an optimal price.

**Data Description:**
The dataset consists of the following columns:

**sample_id:** A unique identifier for the input sample
**catalog_content:** Text field containing title, product description and an Item Pack Quantity(IPQ) concatenated.
**image_link**: Public URL where the product image is available for download.
**Example link**- https://m.media-amazon.com/images/I/71XfHPR36-L.jpg
To download images use download_images function from src/utils.py. See sample code in src/test.ipynb.
**price:** Price of the product (Target variable - only available in training data)
**Dataset Details:**
**Training Dataset:** 75k products with complete product details and prices
**Test Set:** 75k products for final evaluation



<img width="1809" height="732" alt="Image" src="https://github.com/user-attachments/assets/d5d7ef9a-6625-4632-9e5c-3d0febd4a17d" />

# Content-based-recommendation-using-deep-learning
This notebook uses images of shirts as a product and recommends the top 10 shirts closest to the shirt liked by the customer. For that purpose, a neural network classifier is used as a data-driven, visually-aware feature extractor. The latter then serves as input for similarity-based recommendations using a ranking algorithm. Combined with more traditional content-based recommendation systems, image-based recommendations can help to increase robustness and performance, for example, by better matching a customer style. 

As demonstrated in this notebook, the traditional use case is building a scalable robust and accurate recommendation engine with visual data. We are using cosine distance to find the similarity between images and recommending the top K items. This is not affected by brightness of images and settings where pixels are uneven.

In short time a team can run this notebook to find relationship between image data they have and can have similarity metric to use in their business cases. 



For any kind of image search for product recommendations in an ecommerce setup, we are relying on content metadata features which are textual or categorical in nature. Many times, the tags are missing or inaccurate, In this use case we showcase how we can employ deep learning based models to map the objects and features in an image using pretrained model to build a robust and accurate recommendation engine. This improves the quality of our recommendations and removes need to train the corpus as we are using the pretrained model by using transfer learning approach.



It can be used to create image similarity search on any corpus of images to generate recommendation. The concept is very applicable for any kind of image data where we want to do deduplication from set of images. Many times, we end up uploading same image twice in different forms and we can use it to deduplicate the product/form images in few milliseconds.

 

Note: Data used in this notebook has been scraped from google. The data consist of images of shirts which has been extracted by crawling the google images.

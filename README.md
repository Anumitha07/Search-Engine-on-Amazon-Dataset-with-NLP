#This code defines a function search_product(query) that takes a search query as input and returns the top 10 most relevant 
products from the dataset based on the query's similarity to the product titles and descriptions.
#The cosine similarity measures how closely the query matches each product's description and title.
#The dataset is sorted by the similarity scores in descending order, so the most relevant products appear at the top. The function then returns the top 10 results,
showing only the Title, Description, and Category columns for each matching product.
#The sample output shows that the search query for "Watch" mostly returns relevant watch products, but also includes a few
unrelated items (like "Biba Women's Kurta") which may have some similarity in description.

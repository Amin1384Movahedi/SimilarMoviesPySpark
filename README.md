# SimilarMoviesPySpark

### Item Base Collaborative Filtering
- Collaborative Filtering is a technique or a method to predict a user's taste and find the items that a user might prefer on the basis of information collected from a various other users having similar tastes or preferences.
it takes into consideration the basic fact that if person X and person Y have a certain reaction for some items then thay might have the same opinion for other items too.

<h3> User Based: </h3> 

> Here, we look for the users who have rated various items in the same way and then find the rating of the missing item with the help of these users.

<h3> Item Based: </h3> 

> Here, we explore the relationship between the pair of items (the user who bought Y, also bought Z). We find the misiong rating with the help of the ratings given to the other items by the user.

<h2> Similar Movies Project </h2>

- Find every pair of movies that were watched by the same person.

- Measure the similarity of their ratings across all users who watched both.

- Sort by movie, then by similarity strength.

![Item Base Collaborative Filtering Flow](https://timesinternet.in/blog/wp-content/uploads/2020/03/i5.png)


<h3> Cosine Similarity Explained </h3>

> Cosine similarity is described mathematically as the division between the dot product of vectors and the product of the Euclidean norms or magnitude of each vector.

![Cosine Similarity Formula](https://builtin.com/sites/www.builtin.com/files/styles/ckeditor_optimize/public/inline-images/1_cosine-similarity.png)

Cosine similarity is a value bound by a constrained range of 0 and 1.

The similarity measurement is a measure of the cosine of the angle between the two non-zero vectors A and B.

Suppose the angle between the two vectors were 90 degrees. In that case, the cosine similarity will have a value of 0. This means that the two vectors are orthogonal or perpendicular to each other.

As the cosine similarity measurement gets closer to 1, then the angle between the two vectors A and B is smaller. The images below depict this more clearly.

![Cosine Similarity Example 1](https://builtin.com/sites/www.builtin.com/files/styles/ckeditor_optimize/public/inline-images/2_cosine-similarity.png)

![Cosine Similarity Example 2](https://builtin.com/sites/www.builtin.com/files/styles/ckeditor_optimize/public/inline-images/3_cosine-similarity.png)

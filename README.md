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

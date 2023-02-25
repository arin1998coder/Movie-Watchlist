# Movie-Watchlist
A Movie watchlist backend project using Spring Boot and usage of Rest API's to make it interactive and response full.

Lets say you love to watch movies and you are a cinephile.
So by using this application You have the following features :

1.You can add Movies to your watchlist by following 3 ways :

a.You can add movies which you liked in your Movie Watchlist by providing Movie Name , Num of Hours and the IMDB Rating.
b.You liked a Director and would like to keep track of that director , So you can add a director and and his/her information in ur Director Watchlist.
c.You can also save in a Director -> [List of Movies] pair format, incase you want to sort the movies based on the directors.

2.You can delete the Movies from your watchlist 

3.You can delete the director and all of his/her movies from the Watchlist

4.You can empty the whole db.

Project Implementation:

1.To keep it simple i have used HashMap as the db(watchlist) for this project.
2.I have used the Spring MVC architecture to create this project.
3.In the Controller class i have used Spring Annotations to interact with the user's requests and provide the response.
4.For testing the working of the API's i have used POSTMAN.

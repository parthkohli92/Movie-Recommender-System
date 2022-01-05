# Movie Recommendation System

**Content Based Recommender System** recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies (title, genre, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API.

This project runs on the idea of conversion of Tags into Vector and we grab the  **5 Closest vectors** from it and show it known as Cosine Similarity.


Check out the live demo: https://movie-recommendation-system-pk.herokuapp.com/

![image](https://github.com/parthkohli92/Movie-Recommender-System/blob/main/Capture2.PNG)


### What is Cosine Similarity and How does it work? 

Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space.

It is a numerical value, ranges between 0 to 1 which helps to determine how much two items are similar or close to each other on a scale of 0 to 1. This ***similarity score*** is obtained by measuring the similarity between the text details of both of the items.


<p align="center">
  <img width="460" height="300" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR2YL5igRWe3NtOV8S_IAQdSbQT_5CdIZEeEg&usqp=CAU">
</p>


## How do you run this project?

1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the requirements.txt file with the command ```pip install -r reuirements.txt ```
3. Get your API key from [https://www.themoviedb.org/](https://www.themoviedb.org/) (Refer the below section on how to get the API key)
4. Replace YOUR_API_KEY in the 7th line of ```app.py``` and hit save.
5. Open your terminal/command prompt from your project directory and run the file ``` app.py``` by executing the command ```python app.py```
6. Go to your browser and type ```http://127.0.0.1:5000/``` in the address bar.
7. And, there you go!

## How to get the API key?

Create an account in [https://www.themoviedb.org/](https://www.themoviedb.org/), click on the ```API``` link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the ```API``` key in your API sidebar once your request is approved.


# comp9321-ass2

## 19.11.2019
Front end almost finished, The index.html is main page, which gaves user two choices of input - movies name and movie feature. Moviesearch.html is movie name search page. TMDB api are used to fetch data( can be change to our api).
the other page that aims to search by features is simalarly , I will finish later.

### Movie_search Page
    input: movie name
    output : movie card , which contains movie title, release_date, overview, poster, rating average, Genre.
### feature_search Page
    input: Rating, Spoken language, Grenre (both or just one)
    output: same as Movie_search Page

TMDB api I used:
```
`https://api.themoviedb.org/3/search/movie?api_key=e3062f645fde67eecb0c4b0e2bcd7b81&query=${searchtext}&page=1`;
```
 
 change is to our Api when test backend service.

 ## 20.11.2019
 Front finished
 Beside search movie name, user can input Rating, Year, Genre( both or 2 of 3, separated by commes) at one page.

 ## 25.11.2019
 Final version
 -Collaborative Filtering works well, but its performance is restricted by size of dataset.
 -recommend system works prefect based on features given by users.
 -Authorization can be well implemented at backend. I design a login form but still do not figure out how send JWT token back to endback. 
 -i also create a function that aims to record info of each request. it is useful for developer to check request flow.
 -Extra api i used is to get the poster of movie, let website interface beautiful.


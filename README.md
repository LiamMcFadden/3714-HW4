# Flix
Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

---

## Flix

### User Stories

#### REQUIRED (10pts)
- [X] (70pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.
- [X] (10pts) Views should be responsive for both landscape/portrait mode.
   - [X] (5pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [X] (5pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.
- [X] (20pts) Improved the user interface by experimenting with styling and coloring.

### App Walkthough GIF

<img src="https://media.giphy.com/media/x40rRTKKlmfb7rfDWu/giphy.gif" width=250><br>

### Notes
This app was relatively straight forward. However, one challenge I encountered was the creating of a border around the view containing each movie. I had originally assumed that this could be done with something along the lines of `android:borderColor="@color/black"`, however, I was mistaken. To create these borders, I made a simple shape view in the `drawable` directory. I then set this shape as the background for my movie items. 

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids

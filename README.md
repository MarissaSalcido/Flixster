## Flix Part 2

### User Stories

#### REQUIRED (10pts)

- [X] (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [X] (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView.

#### BONUS
- [X] Implement a shared element transition when user clicks into the details of a movie
- [ ] Trailers for popular movies are played automatically when the movie is selected (1 point).
- [X] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
- [X] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [ ] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [ ] Apply the popular ButterKnife annotation library to reduce view boilerplate. (1 point)
- [ ] Add a rounded corners for the images using the Glide transformations. (1 point)

### App Walkthough GIF

<img src="https://i.imgur.com/s2O9gEb.gif" width=250><br>

### Notes

The app would run but not display movies because of a very hidden typo in my code. 

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
------------------------------------------------------------------------------------------------------------------------------
# Flixster
An Android application where you can browse the latest movie releases.

Flixster App for CodePath
# Project 2 - Simple Todo App

Submitted by: Marissa Salcido

Time spent: 2 hours spent in total

## User Stories

The following **required** functionality is completed:

* [x] User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API. 

The following **optional** features are implemented:

* [] Views should be responsive for both landscape/portrait mode.
* [] Display a nice default placeholder graphic for each image during loading
* [] Improve the user interface through styling and coloring
* [] For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. 
     Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='flixster.gif' title='Video Walkthrough' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Android Studio was running very slowly for this project which added time to project completion. 

## License

    Copyright 2019 CodePath

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

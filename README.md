# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [X] (5pts) User can tap a cell to see more details about a particular movie.
- [X] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF

<img src="Yhttps://github.com/kc3585/Flix/blob/master/flix2.gif" width=250><br>

### Notes
The main challenge was fixing the errors with the connections because whenever the superhero tab was clicked, NSException came up. This issue helped me dissolve the problem and find the root cause of the error.

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [X] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [X] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [X] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [X] (2pt) User can view the app on various device sizes and orientations.
- [X] (1pt) Run your app on a real device.

### App Walkthough GIF

<img src="https://github.com/kc3585/Flix/blob/master/flix1.gif" width=250><br>
GIF created with [LiceCap](http://www.cockos.com/licecap/).

### Notes
While building the app, there was a point where the NSException error kept on occurring due to the fact that multiple connections were made to different objects on the storyboard. Old connections were still alive when objects were deleted. This made it difficult to diagnose the problem.

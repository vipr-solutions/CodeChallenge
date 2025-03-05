# VIPR Code Challenge - Movie Review API & Frontend Viewer
Develop a TV & movie review application consisting of:

1. A REST API to store and retrieve reviews
2. A Frontend to display their reviews

## Technical Requirements
* Backend must be written in C# using .Net 7+
  * Expose API endpoints:
    * `POST /media` - Add new movie or TV show
    * `GET /medias` - List all movies and TV shows
    * `POST /media/{id}/reviews` - Add a review (1-5)
    * `GET /medias/{id}/reviews` - Get all reviews
  * Store data in-memory or file
* Frontend (Vanilla JavaScript, Vue, React or whichever you are comfortable with)
  * Should Fetch and display movies and TV shows
  * Allow users to submit reviews
  * Display reviews under each movie

## Considerations
* The API and frontend should work together but does not require authentication.
* frontend doesn't need to be pretty but functional and interact with the API.
* Unit tests would be useful but not essential


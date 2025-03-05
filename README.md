# VIPR Code Challenge - Juniors
## TV & Movie Review API & Frontend Viewer
Develop a TV & movie review application called Mogul, consisting of:

1. A __REST API__ to store and retrieve reviews
2. A __Frontend__ to display their reviews

This repository contains two projects, a starter Api and starter Unit Test project. The Api is based on the Minimal Api convention.

## Technical Requirements
* Backend must be written in __C#__ using __.Net 7+__
  * Expose API endpoints:
    * `POST /media` - Add new movie or TV show
    * `GET /medias` - List all movies and TV shows
    * `POST /media/{id}/reviews` - Add a review (1-5)
    * `GET /medias/{id}/reviews` - Get all reviews
  * Store data in-memory or file
* Frontend (__Vanilla JavaScript, Vue, React__ or whichever you are comfortable with)
  * Should Fetch and display movies and TV shows
  * Allow users to submit reviews
  * Display reviews under each movie

# Getting Started
Please __Fork__ this repository into your own public GitHub account and make sure to install [VS Code](https://code.visualstudio.com/) and the [C# Dev Kit Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)

* A great resource to look at is the Microsoft docs like the [Minimal APIs Docs](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-9.0&tabs=visual-studio-code)
* You likely will need to run `dotnet dev-certs https --trust` as mentioned in the docs when running the solution for the first time.

## Considerations
* The API and frontend should work together but does __not require authentication__.
* frontend doesn't need to be pretty but functional and interact with the API.
* Unit tests would be useful but __not essential__. Unit testing library is xUnit but feel to use what you're comfortable with.
* Database isn't essential
* Using AI isn't frowned upon however be prepared to answer our questions!
* Feel free to have fun and add anything you might like to play with however we estimate a maximum between 3-4 hours to complete this task.

# When you have finished
Please replace this README file with your thoughts and considerations. Perhaps discuss anything else you might have liked to include if this were a real product.

Once you've done that, please email the link to your fork on Github to dotnet[at]viprsolutions.com

__Good luck and Happy Coding!__
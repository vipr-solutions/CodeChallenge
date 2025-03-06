# VIPR Code Challenge (Graduate / Junior)
## TV & Movie Review API & Frontend Viewer  

Welcome to the **VIPR Code Challenge**! Your task is to develop **Mogul**, a simple TV & movie review application consisting of:  

1. A **REST API** to submit/retrieve films and tv shows (media) and to submit/retrieve related reviews.
2. A **Frontend** to capture and display the media and reviews.

This repository provides a starter **API** and **Unit Test** project. The API follows the **Minimal API** convention.  

---

## 📌 Technical Requirements  

### 🔹 Backend (**C# & .NET 7+**)  
- Implement a **REST API** exposing the following endpoints:  
  - `POST /media` - Add a new movie or TV show  
  - `GET /media` - List all movies and TV shows  
  - `POST /media/{id}/reviews` - Add a review (rating: 1-5)  
  - `GET /media/{id}/reviews` - Retrieve all reviews for a movie/TV show  
- Store data either **in-memory** or in a **file**  

### 🔹 Frontend (Any Framework)  
- Use **Vanilla JavaScript, Vue, React**, or any framework you're comfortable with  
- Submit, fetch and display movies & TV shows from the API  
- Allow users to submit reviews  
- Display reviews beneath each movie/TV show  

---

## 🚀 Getting Started  

1. **Fork** this repository to your **public GitHub** account  
2. Install:  
   - [VS Code](https://code.visualstudio.com/)  
   - [C# Dev Kit Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)  
3. Refer to the [Minimal APIs Documentation](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api?view=aspnetcore-9.0&tabs=visual-studio-code)  
4. If needed, run the following command:  

   `dotnet dev-certs https --trust`  

---

## 📝 Considerations  

- The API and frontend should **work together** but **do not** require authentication  
- The frontend doesn’t need to be visually appealing—**just functional**  
- Unit tests are **optional** but encouraged (this repo includes **xUnit**, but you can use what you're comfortable with)  
- A database is **not required**  
- Using AI as a development aid is welcome, but be prepared to discuss your implementation!
- Feel free to add any extra features—but **aim to complete it within 3-4 hours**
- Consider what different/similiar properties movies and tv shows have and how this could be structured

---

## 📩 Submission  

Once you've completed the challenge:  

1. **Replace this README** with your thoughts and considerations:  
   - What challenges did you face?  
   - What would you improve if this were a real product?  
2. **Email** the link to your forked repository to:  
   📧 **dotnet[at]viprsolutions.com**  

---

🎬 **Good luck, and happy coding!** 🚀✨  

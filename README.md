# 8-1-0-assignment

The homework this week will be a little bit different. It will be more similar to a solo project! But you won't be building from scratch. Instead, you will be using code found in the repo below as a reference to build your own app (look in the `1-fellow-tracker-final/` directory):

https://github.com/The-Marcy-Lab-School/8-1-0-express-rest-api-model

You will be tasked with creating a frontend and backend app that lets users manage a playlist of songs.
* The frontend will display the songs and let users create new songs and update/delete existing songs
* The backend will store the songs data, serve the frontend code, and provide API endpoints for manipulating the songs data

## Milestones

You will have one week to complete the app, but here are some milestones that you should aim to hit:

**Day 1 — Create a `Song` model** 

Start by setting up the folder structure for your app. You should have a `frontend` folder containing your React application and a `server` folder containing your server code. Feel free to copy code from the `1-fellow-tracker-final/` directory of the repo above.

Your `Song` model should be a `class` with 5 CRUD capabilities:
* [ ] Create a `Song` instance with at minimum an `id`, a `title`, and an `artist`
* [ ] Get the list of ALL `Song` instances
* [ ] Find a single `Song` instance by its `id`
* [ ] Find and Update the title of a `Song` instance by its `id`
* [ ] Find and Delete a `Song` instance by its `id`

The `Song` class should have a `constructor` and 4 `static` methods.

**Day 2 — Endpoints and Controllers**

By the end of day 2, your server should have a fully functional backend with a model, controllers, and endpoints for performing the 5 CRUD operations: 
* [ ] Get All
* [ ] Get One
* [ ] Create
* [ ] Update
* [ ] Delete

The endpoints should follow REST conventions and should all begin with `/api`

Test your endpoints using the Postman extension (details can be found in the repo above)

**Day 3 — Frontend**

* [ ] Your frontend should be able to make requests to the backend for all 5 CRUD operations and render the resulting data.

Remember, a server application is mostly “boilerplate” (it’s the same every time) so feel free to copy the example applications in the notes and refactor them to suit your needs. Refactoring is the real challenge here, not creating from scratch.

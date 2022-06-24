To start up the app for the first time:

1. Open up a terminal for the back-end of the app.
2. From the root directory, run `cd back-end`.
3. Run `npm install`.
4. Run `npm start`. This will start the server on port 8080.

5. Open up a terminal for the front-end of the app.
6. From the root directory, run `cd front-end`.
7. Run `npm install`.
8. Run `npm start`. This will start the app on port 3000.

9. Set your `NODE_ENV` environment variable to `development`. This will point the front-end to our server running at http://localhost:8080. On Windows, the command to do this is:
`$env:NODE_ENV = 'development'`
For the syntax to do this on other operating systems, refer to (https://www.geeksforgeeks.org/node_env-variables-and-how-to-use-them/).

To see this from the view of user, use this login:

Username: dachschund@gmail.com
Password: ilovedogs678

To see this from the view of an admin, use this login:

Username:
Password:

_______________________________________________________________________________________________________

This was a group Capstone project where we made an adoption page for a fictional animal shelter. Because there were two other group members, I want to
be clear about what I did for this project.

I created the search filters on the search pets site (where you can filter by breed, name, etc.)
I was in charge of most of the database functions. I created the Google Firestore database and made it so pets/news items would get added and deleted.
I made the functions that collects the ids and formated the information in a way that was readable to our front end. I also did the opposite and made
sure data sent to our back end for deleting and adding was readable.
I also made the preview image when uploading a picture of your pet work.

We all helped each other on everything, but generally I worked on database and backend stuff.

Heres a video of me demostrating what I worked on by the midpoint of this project (feel free to stop watching after 2:30).

https://www.youtube.com/watch?v=WOW6QNquEi4

Heres a video of me demostrating what I worked on from the mid point to the end of this project.

https://www.youtube.com/watch?v=pIz61hfzzjE
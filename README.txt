SpeakingBook is a web application inspired by Spotify. It utilizes Ruby on Rails on the backend, a PostgreSQL database, and React.js with Redux architectural framework on the frontend

Database:
Database contains audiobooks and users. Users is a self-joined table for friending users. Images and audio files are stored in a file system. Audiobooks are associated with users. Users can play their own books and books of their friends

Rendering Audiobooks
Books are rendered to two differen components: profile page component and home page component. 
Playbar shows up at the bottom on the page when users hit play button on the audio book component. Playbar continues play while users navigate through the site.

Audioboos detail rendering. 
Contains displays full information about the audiobook and display edit button.

Search.
Users might search books uploaded by them on the profile page

Friending
Users might friend/unfriend other users. Unfriending restricts access to the unfriended user's audiobooks while the unfriended user still has access to that user's audiobooks

Additional functionality
My plan is to add bookmarks to the audiobook playbar, so a user can start playing the book from the place where he/she stopped.



Timeline

Phase 1: Backend setup and Front End User Authentication (2 days)
Objective: Functioning rails project with front-end Authentication

Phase 2: Ab model, API, controllers and components (2 day)
Objective: Ab can be created, read, edited and destroyed through API

Phase 3: Ab components, playbar component(2 days)
Objective: Ab can be created, read, edited and destroyed through front end. Can be played contin.


Phase 4: Friends(2 days)
Objective: Database setup for friends, json, components to display friends

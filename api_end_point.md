HTML API
	Root
		GET / - loads React web app

JSON API
	Users
		POST /api/users
		GET /api/index - shows friends
	Session
		POST /api/session
		DELETE /api/session
	Audiobooks
		POST /api/books/:usersId
		DELTE /api/books/:userId/:id
		GET /api/books/:userId/:id - shows user's books on profile page
		GET /api/books/ - shows books of friends
		PATCH /api/books/:userId/:id - edits user's book
		GET /api/books/:id - shows book's details


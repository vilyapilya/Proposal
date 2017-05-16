{
	currentUser:{
		id: 1,
		username: "user1"
    },
    forms: {
    	signUp: {errors: []},
    	signIn: {errors: []},
    	createBook: {errors: ["title can't be blanck", "author can't be black"]}
    }
    usersBooks: {
    	1: {
    	  title: "War and Peace",
    	  author: "Leo Tolstoy",
    	  description: "A very long story"
        }
    }
    friendsBooks: {
    	1: {
    	  title: "The Raven",
    	  author: "Edgar Allan Poe",
    	  description: "A very sad poem"
        }
    }
}
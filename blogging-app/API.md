# Blogging App 

## JSON Entities

### User 

    {
	    "id": 31,
	    "username": "arnavg",
	    "email":	"arnav@blog.com",
	    "password": "xxxxxxxx",
	    "authToken": "dakjghadlghadlghladhgkgdklgladkgjadlkgd"
	    "bio": 		"writes really good articles!",
	    "image":	"https://imgur.com/ahkbtqe.png"
    }

### Profile 

    {
	    "username": "arnavg",
	    "bio": 		"writes really good articles!",
	    "image":	"https://imgur.com/ahkbtqe.png"
    }

### Article 

    {
	    "id": 134,
	    "title": "How the stock market fell in 2022",
	    "slug": "how-stock-market-fell-2022"
	    "subtitle": "An article about how the stock market had a crash in 2022",
	    "body"	: "This is an article about ..... <b>stock market</b> .... <i>2022</i> .........",
	    "createdAt":  "2022-02-06 03:40:55",
	    "tags"	: ["finance", "stocks"]
    }
	  

### Comment 

    {
	    "id": 1344,
	    "title": "great article",
	    "body" : "this was a great article, loved reading it!",
	    "createdAt: "2022-02-07 03:40:55"
    }

### Errors 
```
{
    "message": "User with username: arnav123 not found"
}
```

## API Endpoints 

### `POST /users` 
create a new user 

### `POST /users/login` 

### `GET /profiles`📄

### `GET /profiles/{username}` 


### `GET /articles` 📄
get all articles (default page size 10)
available filters 

- `/articles?tag=stocks`
- `/articles?author=arnavg`
- `/articles?page=3&size=10`

### `GET /articles/{article-slug}`

### `POST /articles` 🔐
create a new article 

### `PATCH /articles/{article-slug}` 🔐👤
edit an article 


### `GET /article/{article-slug}/comments` 📄 
get all comments of an article 

### `POST /article/{article-slug}/comments` 🔐

### `DELETE /article/{article-slug}/comments/{comment-id}` 🔐👤



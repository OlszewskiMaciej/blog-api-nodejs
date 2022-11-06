You should put your connection string in .env file like this:
```
MONGO_URL = connection_string
```

API examples:

USERS:

POST - /api/auth/login
```
{
    "username": "temp",
    "password": "temp"
}
```

POST - /api/auth/register
```
{
    "username": "testuser",
    "email": "testuser@gmail.com",
    "password": "123456"
}
```

DELETE - /api/users/:userId

PUT - /api/users/:userId
```
{
    "userId": "6335ace42ac4dcdf2609363a",
    "username": "temp",
    "password": "temp"
}
```

GET - /api/users/:userId

&nbsp;

POSTS:

POST - /api/posts
```
{
    "username":"temp",
    "title":"Post title",
    "desc":"Post description"
}
```

DELETE - /api/posts/:postId

PUT - /api/posts/:postId
```
{
    "username":"temp",
    "title":"Updated title",
    "desc":"Updated desc"
}
```

GET - /api/posts

GET - /api/posts/:postId

GET - /api/posts?user=:username

&nbsp;

CATEGORIES:

POST - /api/categories
```
{
    "name": "music"
}
```

GET - /api/categories

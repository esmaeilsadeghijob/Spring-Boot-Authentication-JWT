

````
INSERT INTO roles(name) VALUES('ROLE_USER');
INSERT INTO roles(name) VALUES('ROLE_MODERATOR');
INSERT INTO roles(name) VALUES('ROLE_ADMIN');

````

````
http://localhost:8080/api/auth/signup
{
    "username":"mod",
    "email":"mod@gmail.com",
    "password":"123456",
    "role":["mod", "user"]
}



http://localhost:8080/api/auth/signin
{
    "username":"mod",
    "password":"123456"
}

````
# simple-blog
 Simple blog app

 Is a simple blog application (Techdegree side project) using <b>Sequelize</b>, <b>Express</b> and <b>Pug</b>.

# Features
1. Create blog post with Title, Author and Body.
2. Show all blog post with time when was created. 
3. Update specified post.
4. Delete post.

# Installation

1. Install all dependencies

    ```javascript
        npm install
    ```
2. Run server the server

    ```javascript
        npm start
    ```
3. In <b>/config/config.json</b> change with your database information.

```javascript
    {
    "development": {
        "username": "root",
        "password": null,
        "database": "database_development",
        "host": "127.0.0.1",
        "dialect": "mysql"
    },
    "test": {
        "username": "root",
        "password": null,
        "database": "database_test",
        "host": "127.0.0.1",
        "dialect": "mysql"
    },
    "production": {
        "username": "root",
        "password": null,
        "database": "database_production",
        "host": "127.0.0.1",
        "dialect": "mysql"
    }
}
```


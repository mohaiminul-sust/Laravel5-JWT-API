## Laravel JWT (JSON Web Token) API Scaffold

Laravel API Boilerplate is a ready-to-use simple API boilerplate for stateless APIs mainly for Angular backend.

It also benefits from these pacakages:

* JWT-Auth - [tymondesigns/jwt-auth](https://github.com/tymondesigns/jwt-auth)
* Dingo API - [dingo/api](https://github.com/dingo/api)
* Laravel-CORS [barryvdh/laravel-cors](http://github.com/barryvdh/laravel-cors)

I just made an "integration" work, adding here and there.

Use the **included postman collection file** [laravel5-jwt-api.postman_collection.json](https://gitlab.com/mohaiminul-sust/Laravel5-JWT-API/blob/master/laravel5-jwt-api.postman_collection.json) for integration check. 

## Configuration

As I have already mentioned before, this boilerplate is based on _dingo/api_ and _tymondesigns/jwt-auth_ packages. So, you can find many informations about configuration <a href="https://github.com/tymondesigns/jwt-auth/wiki/Configuration" target="_blank">here</a> and <a href="https://github.com/dingo/api/wiki/Configuration">here</a>.

However, there are some extra options that I placed in a _config/boilerplate.php_ file. Check'em to get mindblown :P


## Cross Origin Resource Sharing

Not implemented just added needed dependencies and configs. Just add cors middleware to activate. Refer to Laravel-CORS [barryvdh/laravel-cors](http://github.com/barryvdh/laravel-cors) for more info ;)

## Feedback

I currently made this project for personal purposes and it is and will always be open for further upgradation. Cheerio :D
## Laravel API Boilerplate (JWT Edition)

Laravel API Boilerplate is a ready-to-use "starting pack" that you can use to build your first API in seconds. As you can easily imagine, it is built on top of the awesome Laravel Framework.

It also benefits from three pacakages:

* JWT-Auth - [tymondesigns/jwt-auth](https://github.com/tymondesigns/jwt-auth)
* Dingo API - [dingo/api](https://github.com/dingo/api)
* Laravel-CORS [barryvdh/laravel-cors](http://github.com/barryvdh/laravel-cors)

With a similar foundation is really easy to get up and running in no time. I just made an "integration" work, adding here and there something that I found useful.

## Configuration

As I already told before, this boilerplate is based on _dingo/api_ and _tymondesigns/jwt-auth_ packages. So, you can find many informations about configuration <a href="https://github.com/tymondesigns/jwt-auth/wiki/Configuration" target="_blank">here</a> and <a href="https://github.com/dingo/api/wiki/Configuration">here</a>.

However, there are some extra options that I placed in a _config/boilerplate.php_ file.

* **signup_fields**: you can use this option to specify what fields you want to use to create your user;
* **signup_fields_rules**: you can use this option to specify the rules you want to use for the validator instance in the signup method;
* **signup_token_release**: if "true", an access token will be released from the signup endpoint if everything goes well. Otherwise, you will just get a _201 Created_ response;
* **reset_token_release**: if "true", an access token will be released from the signup endpoint if everything goes well. Otherwise, you will just get a _200_ response;
* **recovery_email_subject**: here you can specify the subject for your recovery data email;


## Cross Origin Resource Sharing

Not implemented just added needed dependencies and configs. Just add cors middleware to activate. Refer to Laravel-CORS [barryvdh/laravel-cors](http://github.com/barryvdh/laravel-cors) for more info ;)

## Notes

I currently removed the _VerifyCsrfToken_ middleware from the _$middleware_ array in _app/Http/Kernel.php_ file. If you want to use it in your project, just use the route middleware _csrf_ you can find, in the same class, in the _$routeMiddleware_ array.

## Feedback

I currently made this project for personal purposes and it is and will be always opoen for further upgradation. Cheerio :D
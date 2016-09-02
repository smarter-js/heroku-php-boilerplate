# heroku-php-boilerplate

A clone of Heroku's [php-getting-started](https://github.com/heroku/php-getting-started) with an emptied web (dist) directory. Great for cloning into existing web projects.

## Deploying

```sh
git clone https://github.com/smarter-js/heroku-php-boilerplate.git 
cd php-getting-started
heroku create
```
Copy websites files to `web` directory.

```sh
git add .
git commit -m 'Initial commit'
git push heroku master
heroku open
```

## Documentation

For more information about using PHP on Heroku, see these Dev Center articles:

- [Getting Started with PHP on Heroku](https://devcenter.heroku.com/articles/getting-started-with-php)
- [PHP on Heroku](https://devcenter.heroku.com/categories/php)

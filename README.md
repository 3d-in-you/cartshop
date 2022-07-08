# CARTSHOP
Welcome to Our Repository, our time will be long kids, keep your smile like evil clowns and we will have a beautiful day together in the future.

# Development
## Cloning Project
Go to directory where the project will cloned.

Using HTTPS
```
git clone https://github.com/3d-in-you/cartshop.git
```

Using SSH
```
git clone git@github.com:3d-in-you/cartshop.git
```

## Running Project
* To run the project, first install the composer package
```
composer install
```

* Setup .env
```
cp .env-example .env
```
Then update the credential inside `.env`


* Finally run the project
```
php artisan serve
```

## Front End
* Add remote repository
Using HTTPS
```
git remote add origin https://github.com/3d-in-you/cartshop.git
```

Using SSH
```
git remote add origin git@github.com:3d-in-you/cartshop.git
```

* Before started, checkout to branch `dev-frontend` first
```
git checkout dev-frontend
git pull
```
* Before push commit to remote, make sure to check current branch is `dev-frontend` then simply push with
```
git push
```
* Do not push directly to master

## Back End
* Add remote repository
Using HTTPS
```
git remote add origin https://github.com/3d-in-you/cartshop.git
```

Using SSH
```
git remote add origin git@github.com:3d-in-you/cartshop.git
```

* Before started, checkout to branch `dev-backend` first
```
git checkout dev-backend
git pull
```
* Before push commit to remote, make sure to check current branch is `dev-backend` then simply push with
```
git push
```
* Do not push directly to master

# NOOB-FRIENDLY-LARAVEL
Nothing I just recently learned Laravel with confidence well some confidence, but not completely mastered.

composer create-project laravel/laravel AnyProjectName

composer install (get inside the AnyProjectName file)

npm install

npm run watch (and then create another cmd) or you can try "npm run dev", but you have to do it everytime you try to update something and it's a hassle. All I can say that "I told you so".

php artisan make:controller AnyControllerName

php artisan make:model AnyModelName

php artisan serve 

to connect the blade.php there are four things in mind:

- web.php
- Controllers
- Models
- .env

tip! in web.php old way and new way of routing do not mix, just like oil and water.

the "Route::get" thingy you can open it directly to see it in action or just view it to check something without further requirement

the "Route::post" thingy you can open it but it will throw an error because it is a post and post parameter always needs something first like give me "something" before you can enter the place mentally unharmed.

oh by the way the string data type is not what you think it was... yeah it does something when you do this thing "{{}}", "{{$anyvariablename}}" then it would result something else.

laravel always love to log things so whenever you try to insert a data to MySQL DB it will message you column missing something yada yada "created-at" and "updated-at" if I remember correctly. It's either you create a column manually in your localhost/phpmyadmin thingy like a little w@nk or you can tell inside the class of your chosen model to f@#$ off by "$timestamps = false;".

As for the making a query in laravel just search eloquent and apply it in a desired controller file. It also always ends in get();

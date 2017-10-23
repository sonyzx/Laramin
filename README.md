<p align="center"><a href="https://github.com/simoebenhida/Laramin" target="_blank"><img width="400" src="https://i.imgur.com/XQ57dWg.png"></a></p>


# **L**aramin - Small Laravel Admin


<hr>

After creating your new Laravel application you can include the Laramin package with the following command:

```bash
composer require simoja/laramin
```

Next make sure to create a new database and add your database credentials to your .env file:

```
DB_HOST=localhost
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret
```

Add the Laramin service provider to the `config/app.php` file in the `providers` array:

```php
'providers' => [
    // Laravel Framework Service Providers...
    //...

    // Package Service Providers
    Simoja\Laramin\LaraminServiceProvider::class,

    // ...

    // Application Service Providers
    // ...
],
```

Lastly, we can install laramin with simply run It Will Add Some Dummy Data

```bash
php artisan Laramin:install
```
You will Have Three Config Files Where you can update the Data As You Wish :

config/laramin.php
config/laratrust.php
config/laratrust_seeder.php


And we're all good to go!

To connected There is some dummy data added you can check on Database

>**email:** `superadministrator@app.com`
>**password:** `password`

### Inspired By :

<a href="https://github.com/santigarcor/laratrust">Laratrust</a> For The User Permissions
</br>
<a href="https://github.com/the-control-group/voyager">Voyager</a> The Idea of making a simple Admin Panel

### Demo
Comming Soon

### Contributing

You are more than welcome to contribute to this repo with anything you think is useful. fixes are more than welcome.



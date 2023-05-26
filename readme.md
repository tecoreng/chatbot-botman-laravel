# Laravel - Create Simple Chatbot using Botman

![laravel chatbot botman](https://i.ibb.co/dg3NSNy/tecoreng-laravel.jpg)


# Installation and running

#### 1. Install Laravel
first of all we need to get fresh Laravel application using bellow command, So open your terminal OR command prompt and run bellow command.

```bash

composer create-project --prefer-dist laravel/laravel blog

```

#### 2. Install Botman 
In this step we will install botman composer package and also install botman web driver. so we need to run following both command to install botman.

```bash

composer require botman/botman

```

#### 3. Install Botman Driver

```bash

composer require botman/driver-web

```

#### 4. Create Configuration File
This step is not required to follow. But you can create configuration file for driver and cache. so let's create bot file on config folder and write code like as i gave you bellow:

##### config/botman/config.php

```bash

<?php
  
return [
   
    'conversation_cache_time' => 40,
  
    'user_cache_time' => 30,
];

```
##### config/botman/web.php

```bash

<?php
  
return [
   
    'matchingData' => [
        'driver' => 'web',
    ],
];

```

#### 5. Run application

rename .env.example file to .env and set your configuration.

```bash

php artisan serve

```

Now you can open bellow URL on your browser:


```bash

http://localhost:8000

```


# Social media Link	

<a href="https://www.facebook.com/Tecoreng" target="_blank"><img src="https://www.vectorlogo.zone/logos/facebook/facebook-icon.svg" width="40" height="40"/></a>
<a href="https://www.instagram.com/Technical_Core_Engineers" target="_blank"><img src="https://www.vectorlogo.zone/logos/instagram/instagram-icon.svg" width="40" height="40"/></a>
<a href="https://twitter.com/tecoreng" target="_blank"><img src="https://www.vectorlogo.zone/logos/twitter/twitter-icon.svg" width="40" height="40"/></a>
<a href="https://linkdin.com/company/tecoreng" target="_blank"><img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" width="40" height="40"/></a>
<a href="https://in.pinterest.com/TechnicalCoreEngineers" target="_blank"><img src="https://www.vectorlogo.zone/logos/pinterest/pinterest-icon.svg" width="40" height="40"/></a>
<a href="https://medium.com/@Tecoreng" target="_blank"><img src="https://www.vectorlogo.zone/logos/medium/medium-icon.svg" width="40" height="40"/></a>
<a href="https://dribbble.com/TechnicalCoreEngineers" target="_blank"><img src="https://www.vectorlogo.zone/logos/dribbble/dribbble-icon.svg" width="40" height="40"/></a>
<a href="https://www.behance.net/Tecoreng" target="_blank"><img src="https://www.vectorlogo.zone/logos/behance/behance-icon.svg" width="40" height="40"/></a>
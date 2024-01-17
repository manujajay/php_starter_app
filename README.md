# Basic PHP Web App

This repository contains the basic setup for a PHP web application. Follow these steps to get started.

## Step 1: Install a Local Server Environment

### For Windows or Mac:
- Install XAMPP from [Apache Friends](https://www.apachefriends.org/index.html).

### For Linux:
- Install LAMP stack using your distribution's package manager.

## Step 2: Create a Simple PHP File

1. Open the `htdocs` folder in your XAMPP installation directory.
2. Create a new folder named `php_starter_app` (or just clone this repo into the `htdocs` folder - then ignore steps 3 and 4).
3. Inside `php_starter_app`, create a new file named `index.php`.
4. Edit `index.php` to include the following code:

    ```php
    <!DOCTYPE html>
    <html>
    <head>
      <title>My PHP App</title>
    </head>
    <body>
      <?php 
      echo "<h1>Hello, World!</h1>"; // This line outputs a header tag with Hello, World!
      ?>
    </body>
    </html>
    ```

## Step 3: Run Your PHP File

1. Open XAMPP Control Panel and start Apache.
2. Open a web browser and go to `http://localhost/myapp/`.
3. You should see "Hello, World!" displayed.

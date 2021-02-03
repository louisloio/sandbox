https://louisloio.github.io/sandbox/style/app.css

# Sandbox

## How to use 

1. Clone or download the repository into local foder of your machine

2. Create any .scss file into custom or add folder 

3. Download Koala application to compile the app.scss. When Koala is running it will update new app.css and app.css.map automatically each time you save modifications.
http://koala-app.com/

4. Open index.html to visualise your changes
   
## Folder and files

- Custom folder is for overide you do on bootstrap
- Add folder is for everything you add to bootstrap such as new components style
- node_modules/bootstrap folder is the source folder of Bootstrap v4.4.x fell free to update it with NPM
- style/app.scss is the main file to compile app.css amd app.css.map
- index.html is the main file with a few bootstrap components

## Start your one page

```
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="style/app.css">

    <title>louilo design</title>
  </head>
  <body>



    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
  </body>
</html>

```

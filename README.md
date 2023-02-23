# My Portfolio

- [My Portfolio](https://sbrycbc.github.io/my-portfolio/ "My Portfolio")

# to use bootstrap.scss

- npm init

- npm i bootstrap

- npm i npm-run-all

- npm i sass

- npm i live-server

- import bootstrap.scss to main.scss (node_modules/bootstrap/scss/bootstrap.scss)

      @import "../node_modules/bootstrap/scss/bootstrap";

- update script tag of package.json

            "scripts": {
             "start":"run-p watch watch:styles",
            "watch":"live-server",
            "watch:styles": "sass scss:styles --watch"
            },

- npm start for creating main.css and main.css.map

- link main.css in html

- add index.html body bootstrap script file - (for dropdown menu and carousel)

          <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" 
          integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous">
          </script>

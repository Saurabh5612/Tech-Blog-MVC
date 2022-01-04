# Tech-Blog-MVC
# Description
We were asked to build a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. This application follows MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

This application was built from scratch using Express Handlebars, MySQL, Sequelize, dotenv, and bcrypt. The CSS Framework used was Bulma.
# Usage
To run locally, after cloning repo and navigating to the root folder:

mysql -u root -p

source db/schema.sql

quit

npm run seeds

npm start

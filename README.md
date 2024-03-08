# Api-pp Readme
==============

This repository contains the code for a simple API. That will be used for a social Media site.

[Link to deployd site!](https://api-pp-d82112337ea8.herokuapp.com/)

## Prerequisites

To run this API, you will need to have Node.js and npm installed on your system. You can download and install Node.js from the [official website](https://nodejs.org/).

## Features

With this API you can post pictures, like pictures and follow other users.
You can also create an account.


## Testing

For testing I have tested that users can post and other users can se the post,
using the built in test.py files.

## Deployment

The project is deployd using heroku.

using the following steps:

1. Create a project on Heroku and open settings.
2. In Config Vars add 'COUDINARY_URL' as a key and add your cloudinary link as value.
3. In Config Vars add 'DATABASE_URL' as a key and add your link to your database as value.
4. In Config Vars add 'DISABLE_COLLECTSTATIC' as a key and add '1' as value.

5. Open th deploy tab in heroku
6. select connect to github and then you search for your repo and connect it.

7. In settings.py, in the ALLOWED_HOSTS list, copy your ‘... .herokuapp.com’ string.

## credits

* [Code Institute](https://codeinstitute.net) especially the Django Rest Framework project. almost all of the code is from th drf api project.

* [Heroku](heroku.com)

* [ElephantSQL](ElephantSQL.com)




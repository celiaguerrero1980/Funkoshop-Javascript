# Funkoshop

Final Challenge of the Fullstack Development course with Javascript and NodeJS at CaC.

## Technology Stack

**Design:** Figma

**Front-End:** EJS, CSS, Javascript

**Back-End:** MVC (Architecture), NodeJS, Express, BcryptJS 

**Database:** MySQL, Sequelize(ORM)

## Get started 🚀

These instructions will allow you to get a copy of the project running on your local machine.

### How to install

> [!IMPORTANT]
> You need to have already installed updated versions of NodeJS and NPM on your machine.

First, you have to download (.zip) or clone the project repository as follows:

```bash
  git clone https://github.com/celiaguerrero1980/Funkoshop
```
Now that you have the project, you can open it in your code editor and from the terminal, install the dependencies as follows:

```bash
  npm install
```
Now only the database part is missing to make your project fully functional.
> [!TIP]
> I recommend you to create an account in AlwaysData and once you are logged in, go to the 'Databases' section to create a MySQL database and also, a user so you can access it. When you have finished that, you can go to https://phpmyadmin.alwaysdata.com/ and that's it! Now you can access with that user to your database.

You almost have everything ready, there is only one step left and that is to create in your project an .env file, which must contain the access information to your database. This file must contain the following:

PORT= 3000
DB_NAME= 'database name'
DB_USER= 'database username'
DB_PASSWORD= 'database password'
DB_HOST= 'xxxxxxx.alwaysdata.net'


### Deployment

To deploy the project locally:

```bash
  npm start
```
Or just click here: https://node-test-sigma-beige.vercel.app/

> [!NOTE]
> Vercel is a free server. It is possible that you may experience failures. In that case, wait a moment and reload the site.   
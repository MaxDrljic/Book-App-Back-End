This is the back-end code for the book application which uses Goodreads API to fetch books data, and it is made with React & Redux. Also, I made user authentication so people can login, register and save books they like. 

To make the whole application work, you will need the Book-App-React code, as well as NodeJS, MongoDB and Yarn package manager. Be sure to download the files from the official websites, just Google the things you need to download.

1. Clone the repo.

2. cd into project and do `npm install`.

3. Be sure to run MongoDB. On their official website, you can find how to set it up if you haven't already. Nice addition would be to install Robo3T, which is a visual representation for Mongo databases. This way it is much easier to add, update or remove records in your database.

4. Rename env-sample to `.env`.

5. You need to add these lines to your .env :
    HOST=
    EMAIL_HOST=
    EMAIL_PORT=
    EMAIL_USER=
    EMAIL_PASS=
    GOODREADS_KEY=
    
6. Add your localhost(mine is 3000) to HOST, and for the EMAIL variables, I used `mailtrap.io`. Make an account, set everything up, create inbox with the name you want, and you should see the details of your inbox, under SMTP. Add those values to your .env EMAIL variables.

7. Make an account on `goodreads.com`. Set everthing up and go in API section: `goodreads.com/api`. Click on the link where it says `developer key`. Generate the developer key and add it to your .env GOODREADS_KEY variable.

8. Execute `yarn start` to start the application.

If you want to change config files you can do it in package.json and yarn.lock, and check the config in .eslintrc to setup eslint.

<h1>Recipe API</h1>

<p>This is an API used to perform CRUD actions on a MongoDB database, and created using Node.js/Express.js.</p>

<h2>Setting up a config.env file</h2>
<p>This project is not in production - to recreate the required database for this project please make an account with MongoDB.
  Then, select the 'Connect' option on this database and then the 'connect your application' option. Ensure that Node.js is selected as the driver
  and make note of the connection string. Ensure that an account is setup within 'Database Access' and make note of the password.</p>
  
<p>Your config.env file should contain the following fields using information obtainer from MongDB:</p>
<br/>
  
KEY | DESCRIPTION
--- | ---
NODE_ENV | This should be set to 'development' for testing.
PORT | A port number should be specified. If one is not provided this will default to 3000.
DATABASE | This should be the connection string obtained above, with 'password' replaced with 'PASSWORD' in upper case.
DATABASE_PASSWORD | This is the password obtained under 'Database Access' above.
  
<br/>
You can run the local server using ```npm run start```.

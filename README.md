<h1>The Universal Auth System</h1>
<h3>Using The MERN Stack Incling Mysql</h3>
<article>
the project is divded to two separte projects
<h4> 1- The Client side</h4>
<p>- containing the react project <strong>Front-End<strong></p>
<p>- the client Auth Functions and storing user tokens methods</p>
<p>- powered with the <strong>ReactBootstrap</strong> package for styling perposes</p>
<p>- using <strong>JWT</strong> package to create,work,decode tokens</p>
<p>- <strong>Axios</strong> package used to crete the http requests</p>
---------------------------------------------------------
<h4> 1- The Server side</h4>
<p>- containing the Node project <strong>Back-End<strong></p>
<p>-  the server Auth Main Function --> <strong>(Register,login,logout)</strong></p>
<p>- verfiy mail by sending otp from the server to the client mail <strong>Using NodeMailer</strong></p>
<p>- Forget password by sending new pass from the server to client mail & ask him to change it once logged in again</p>
<p>- update Client account Password & verfiy the user before updating <strong>using JWT Verfiy</strong></p>
<p>- Refresh Tokens function to update user Access token in case of expiration</p>
</article>
-----------------------------------------------------------
<article>
<h4>Setup Steps</h4>
<p>- install Docker And init the docker compose file included in the project <strong>Optinal</strong><p>
<p>create db for your project in <strong>phpmyadmin</strong> interface</p>
<p>- init the <strong>db.sql</strong> file included in the main project in <strong>phpmyadmin</strong> interface mysql manager or any way you like to create the db & start working<p>
<p>- open the 2 projects in seprate windows</p>
<p>- init <strong>npm install</strong> in them to install contained packages</p>
<p>- create the <strong>.env</strong> file on the server side and put the following info in it with the same labels
</br>
<span>
DATABASEHOST
,DATABASEUSER 
,DATABASEPASSWORD
,DATABASE
</br>
JWT_SECRET
,JWT_REFRESH_SECRET
,JWT_EXPIRES_IN
</br>
PORT
</br>
MAIL_SERVER
,MAIL_USER
,MAIL_PASS
</span></p>
<p>- init command <strong>npm start</strong> in the 2 separte projects</p>
<p>- strat testing and add-on the rest of your project</p>
</article>

<article>
<h4>Note:</h4>
<p>- The system might have some problems if founded please report it to me so i can fix it in the future</p>
<p>- please if there is any comments for better exprenice or security send to me to help the system be better</p>
<p>- the technolgy which used to create the server is Express Genertaor you can check it out from <a href="https://expressjs.com/en/starter/generator.html">here</a></p>
<p>- in the server mailing section you can use your personal Gmail account to send the mails for testing but you need to Allow security option in Gmail called <strong>Allow less secure apps</strong></p>
</article>
----------------------------------------------------------------
<article>
<h4>Used Techs Reference:</h4>
<p><a href="https://nodejs.org/en/l">Node.js</a></p>
<p><a href="https://expressjs.com/">Express.js</a></p>
<p><a href="https://reactjs.org/">React.js</a></p>
<p><a href="https://jwt.i">JWT</a></p>
<p><a href="https://www.npmjs.com/package/bcrypt">Bcrypt</a></p>
<p><a href="https://nodemailer.com/about/">Nodemailer</a></p>
<p><a href="https://www.npmjs.com/package/uuid">UUID</a></p>
<p><a href="https://react-bootstrap.github.io/">ReactBootstrap</a></p>
<p><a href="https://getbootstrap.com/">Bootstarp</a></p>
<p><a href="https://axios-http.com/">Axios</a></p>
<p><a href="https://www.npmjs.com/package/dotenv">Dotenv</a></p>
<p><a href="https://www.npmjs.com/package/nodemon">Nodemoon</a> for testing</p>
<p><a href="https://hub.docker.com/">Docker</a> for DB testing</p>
</article>

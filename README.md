# Installation  
 *express  
 *mongo  
 *sudo npm install jsonwebtoken : token  


# Getting Started on Heroku with Node.js  
  * http://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction  

# Challenge  
 * Procfile:  
   Procfile should be "npm start", but when I first set up heroku deployment with node.js,  
   I did with "node start", so localhost was working, but my heroku was not not working, took me days to find out the error.  
   * http://stackoverflow.com/questions/30991736/heroku-procfile-running-npm-start

# JsonWebtoken set up  
 * Jsonwebtoken should be set up before index routing.  
      jsonwebtoken
      app.use('/ingredients/api*', authApi);
      app.use('/', index);
      app.use('/users', users);  

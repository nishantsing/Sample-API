# Sample-API
### Example of a basic API

npm i -g json-server
json-server --watch db.json\

### Adding to Github
Creating new repository in github. Cloning the repository to local machine using 
git clone <url>

In local repository after making changes
git add .
git commit -m 'created json db'
git push origin Head


### Deploying to Heroku

Create an heroku account. Install heroku cli
npm i -g heroku 
heroku --version
heroku login
heroku create my-sample-api
git push heroku main
heroku open

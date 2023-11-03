# Cyber Buddy Backend Server Heroku Deployment

To deploy to Heroku:
- make sure to have a Heroku account
- clone the repository:
```
git clone https://github.com/Binbasri-in/try_hack_deploy.git
```
- login to Heroku CLI:
```
heroku login
```
download Heroku from <a href="https://devcenter.heroku.com/articles/heroku-cli">here</a>

- create a new Heroku app
```
heroku create my-app
```
- connect it to your git repository:
```
git remote add heroku https://git.heroku.com/my-app.git
```
- push changes to your heroku app:
```
git push heroku master
```
- click on the link that appears and your application is there

you may run to some problems so here are some popular issues you may encounter
- Add the enviroment variables like `OPENAI_API_KEY`.
- If you are using Flask_CORS the you need to add the Environment variable `DYNO_CORS_HEADERS=*`

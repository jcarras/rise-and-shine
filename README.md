rise-and-shine
==============

Simple app to keep heroku server from going idle.

Rock and roll using these steps:

1) Create a new Heroku app.
2) Add your new Heroku app's URL to config.json (pingServerUrl)
3) Add the urls you want to ping to config.json (urlsToPing)
4) Add your newly created Heroku repo to this git repo's remote using (git remote add heroku  "git@heroku.com:my-new-heroku-repo.git").
5) "git push heroku" to deploy your Heroku app and start keeping your apps alive :)
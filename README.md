rise-and-shine
==============

Simple app to keep heroku server from going idle. br

Rock and roll using these steps: br

1) Create a new Heroku app. br
2) Add your new Heroku app's URL to config.json (pingServerUrl) br
3) Add the urls you want to ping to config.json (urlsToPing) br
4) Add your newly created Heroku repo to this git repo's remote using (git remote add heroku  "git@heroku.com:my-new-heroku-repo.git"). br
5) "git push heroku" to deploy your Heroku app and start keeping your apps alive :)
node app.js


heroku git:remote -a https://github.com/hansolro2701/wegoyougoclient


heroku open --app wegoyougo

heroku create wegoyougo

heroku addons:create heroku-postgresql:hobby-dev --app wegoyougo


heroku logs --tail




npm install -g heroku

heroku --version


heroku login

heroku login -i


heroku create
heroku logs --tail
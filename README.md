node app.js


cd myapp
heroku config:set PORT=3000 



heroku login

postgres://euaauxqintrqam:3f18c602fcc3e8a272ff3357e5e496f6d7a54e758474b167f2e0b63a433c16e7@ec2-54-90-13-87.compute-1.amazonaws.com:5432/dbnlj49p6qnqbn
postgres://euaauxqintrqam:3f18c602fcc3e8a272ff3357e5e496f6d7a54e758474b167f2e0b63a433c16e7@ec2-54-90-13-87.compute-1.amazonaws.com:5432/dbnlj49p6qnqbn
const db = {
  database: "wegoyougo",
  connectionLimit: 10,
  host: "my8001.gabiadb.com",
  user: "wegoyougo",
  password: "wamc2701!!"
};

heroku git:remote -a https://github.com/hansolro2701/wegoyougoclient




heroku open --app wegoyougo

heroku create wegoyougo

heroku addons:create heroku-postgresql:hobby-dev --app wegoyougo


heroku logs --tail




npm install -g heroku

heroku --version



heroku login -i


heroku create
heroku logs --tail
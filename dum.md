touch app.js
touch Dockerfile
touch .dockerignore
npm init -y
npm i express
npm init -y
npm i express
"type":"module"
npm i -D nodemon | npm i nodemon --save-dev
"start": "node app.js"
"dev": "nodemon app.js"
npm i ejs
npm i mongoose
"type": "module"
npm run start 
npm run dev

docker run -v %cd%:/app -p 3000:3000 -d --name node-app img
docker run -v $(pwd):/app -p 3000:3000 -d --name node-app img
#working on power shell bash
docker run -v ${pwd}:/app -p 3000:3000 -d --name node-app img 




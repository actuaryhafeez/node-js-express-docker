mkdir resume-project
cd resume-project
mkdir controllers
mkdir views
mkdir -p public/css 
mkdir public/js 
mkdir public/images
mkdirt views/partials

touch views/home.ejs
touch views/services.ejs
touch views/skills.ejs
touch views/contact.ejs

touch views/partials/header.ejs
touch views/partials/footer.ejs
touch views/partials/sidebar.ejs

touch controllers/homeController
touch controllers/skillsController
touch controllers/servicesController
touch controllers/contactController

touch app.js
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



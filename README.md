# learningBootstrap4
This is my practice file created along the way of learning Bootstrap 4, excited to explore more.

Installing Bootstrap in Angular6 (taken from https://stackoverflow.com/questions/43557321/angular-4-how-to-include-bootstrap)
npm install bootstrap --save
npm install jquery --save
npm install popper.js --save

And edit angular.json as below (../ had to be removed to point libraries to correct path)

"styles": [   
    "node_modules/bootstrap/dist/css/bootstrap.min.css",
    "styles.css"
  ],
  "scripts": [  
    "node_modules/jquery/dist/jquery.min.js",
    "node_modules/popper.js/dist/umd/popper.min.js",
    "node_modules/bootstrap/dist/js/bootstrap.min.js"
  ],

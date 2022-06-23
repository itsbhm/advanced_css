Commands used in this module:

npm init\
npm install node-sass --save-dev \
npm install jquery --save \
npm uninstall jquery --safe \
npm install live-server -g \
npm run compile:sass \
live-server \
"compile:sass-max": "node-sass assets/sass/main.scss assets/css/style.css -w" \
"compile:sass-min": "node-sass assets/sass/main.scss assets/css/style.css -w --output-style compressed"
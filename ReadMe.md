#### front-end dev project skeleton

##### working: jshint, js, img, less, html, jade, fonts, BrowserSync(live-reloading of img's,css, js, html), s3 deploy

##### demo: http://front-end-skel.s3-website-us-west-1.amazonaws.com/

##### setup: cat ReadMe.md | sh

    npm install -g bower gulp
    npm install
    bower install
    gulp

###### s3 deploy checklist:
###### 1. select the right ID/key CREDENTIALS Pair (IAMS user recommended)
###### 2. pass the right s3 BUCKET NAME to 'aws-deploy' in gulpfile.js
###### 3. make sure your credentials have ACCESS to your bucke
###### 4. follow http://amzn.to/1BoEmps to make sure gulp can FIND your credentials


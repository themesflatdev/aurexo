# SCSS
compile SCSS to CSS, install SASS:

# Install SASS 
npm install -g sass

#Compile SCSS:
sass assets/scss/app.scss:assets/app.css

# Developer mode (auto compile on changes)
sass --watch assets/scss/app.scss:assets/app.css
OR
sass --no-source-map --watch assets/scss/app.scss:assets/app.css

 
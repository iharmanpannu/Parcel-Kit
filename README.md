# Parcel Starter Kit
* [Live Demo](https://parcelkit.surge.sh)
<br>

### First install Parcel using Yarn or npm:

Yarn:

* yarn global add parcel-bundler

npm:

* npm install -g parcel-bundler

### Next install all dependencies
* npm install or 
* yarn

Parcel has a development server built in, which will automatically rebuild your app as you change files and supports hot * module replacement for fast development.

* parcel index.html

Now open http://localhost:1234/ in your browser. You can also override the default port with the -p <port number> option.

Use the development server when you don't have your own server, or your app is entirely client rendered. If you do have your own server, you can run Parcel in watch mode instead. This still automatically rebuilds as files change and supports hot module replacement, but doesn't start a web server.

* parcel watch index.html

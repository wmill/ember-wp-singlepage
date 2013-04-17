A very simple example showing Ember.js and wp-json-api integration.

Current problems:
- The loading doesn't work well.  If the server responds slowly than the page will load before there is any data and crash.
- Right now Post objects are bound, but I don't know how to bind a view/template to an array.  So calling Post.set will result in a view update.  But adding a new item will not.  
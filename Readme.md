Vue Loading Ajax NProgress
==========================

This is a plugin for add nprogress on all ajax calls from vuejs.


On your app.js

```javascript

import Loading from "vue-loading-ajax-nprogress"
import 'nprogress/nprogress.css'
Vue.use(Loading);

```

On your components that call ajax.

```javascript

//On your method
//to show
this.$loader.show();
//to hide
this.$loader.hide();

```

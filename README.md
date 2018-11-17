# ionic4-tabs-lazy-load-reproducer
A repo to reproduce a bug with lazy loading tab content.  This repo was created using the ionic CLI and minor changes made on top of it.

```
$> ionic start kajal tabs --cordova --type=angular 
```

## Steps

* Clone this repo
* Run the following:

```
$> npm install
$> npm run start
```

* The app will come up in http://localhost:4200.  When you visit the ``Contacts`` tab, you can notice the heading is pulled down.  Opening up devtools and adding the class ``ion-page`` to the corresponding page element fixes the styling.


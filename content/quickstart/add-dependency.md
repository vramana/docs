# Adding a dependency

In this step you'll learn how to add a dependency to your package.

Add the colors module which will allow you to print the message in different
colors:
```
npm install colors --save
```

This has downloaded the colors module to the `node_modules` directory and added
the dependency to the `dependencies` key in your `package.json`.

Now use the colors module in your `index.js` file:
```
var colors = require("colors");

console.log(colors.rainbow("Hello World"));
```

<div class="test">
Test: Run `node index.js`. `Hello World` should be output in rainbow colors.
</div>

<a class="btn btn-lg btn-default" href="#" data-toggle="modal" data-target="#js-report-problem-modal">
Report a problem
</a>
<a class="btn btn-lg btn-primary js-button js-complete">
I have a rainbow "Hello World"
</a>

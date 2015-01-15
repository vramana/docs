# Creating a package

In this step you will create a package that can be published to the npm registry.

The only requirement for a package on npm is that it have a `package.json` file,
which contains metadata about what the package is.

npm can create a `package.json` file by guiding you through some questions about
your package:

```sh
$ mkdir npm-quickstart
$ cd npm-quickstart
$ npm init
```

These are the questions that you will be asked. You can just press enter for all
of these questions to accept the default.
```sh
Press ^C at any time to quit.
name: (@linclark/npm-quickstart)
version: (1.0.0)
description:
entry point: (index.js)
test command:
git repository:
keywords:
author:
license: (ISC)
```

Then it will show you the `package.json` file that it will write. Type `yes` to
accept this.

<div class="test">
Test: You should now have a `package.json` file in your directory.
</div>

<a class="btn btn-lg btn-default" href="#" data-toggle="modal" data-target="#js-report-problem-modal">
Report a problem
</a>
<a class="btn btn-lg btn-primary js-button js-complete">
I have a package.json file
</a>

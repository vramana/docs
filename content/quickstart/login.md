# Logging in on the command line

In this step you will log in as your user from the command line. The credentials
you use will be saved to a file on your computer so you only have to do this
once.

```sh
$ npm login
Username: your_user
Password:
Email: (this IS public) your_user@gmail.com
```

<div class="test">
Test: Your credentials should be saved on your computer.

```sh
$ npm config ls
...
; userconfig /Users/your_user/.npmrc
//registry.npmjs.org/:always-auth = false
//registry.npmjs.org/:email = "your_user@gmail.com"
//registry.npmjs.org/:username = "your_user"
email = "your_user@gmail.com"
```
</div>

<a class="btn btn-lg btn-default" href="#" data-toggle="modal" data-target="#js-report-problem-modal">
Report a problem
</a>
<a class="btn btn-lg btn-primary js-button js-complete">
I have logged in
</a>

# Updating your package

In this step you will update your package to include your new functionality.

Because you didn't add any new features or break any existing features,
this will be a patch release of your package. This means you need to increment
the last part of the version number (to learn about semantic versioning, check
out our [video](/getting-started/semantic-versioning)).

You can do this by running:
```
npm version patch
```

This will also add a tag to your git repository.

Now run:
```
npm publish
```

<div class="test">
Test: Your package should now be updated in the registry, and this will be
reflected on the [package page]().
</div>

<a class="btn btn-lg btn-default" href="#" data-toggle="modal" data-target="#js-report-problem-modal">
Report a problem
</a>
<a class="btn btn-lg btn-primary js-button js-complete">
I have updated my package
</a>

# meteor-collection-autodoc
A command-line script that runs alongside a Meteor app during development to help you generate docs for collection schemas, on the fly.

## Installation:
Alias the coldoc script:
```
alias coldoc="/absolute/path/to/coldoc"
```

## Usage:
Show docs for one collection:
```
coldoc Admins
```

Show docs for all collections:
```
coldoc ""
```

Show docs for a particular file:
```
coldoc /my/js/directory/file.js
```

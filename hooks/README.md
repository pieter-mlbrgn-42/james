# James

Git hook package

## Installation

Add to `composer.json`

```json lines
"repositories": [
    {
        "type": "vcs",
        "url":  "git@github.com:pieter-mlbrgn-42/james.git"
    }
],
```

Then `composer require --dev pieter-mlbrgn-42/james`

And add also
```json lines
"post-update-cmd": [
  "vendor/pieter-mlbrgn-42/james"
],
```

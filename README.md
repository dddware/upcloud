# upcloud

Javascript plug-in to enable sending client files to cloud hosting platforms

## Introduction

**upcloud** is meant to provide an alternative way to send your users files such as invoices, legal documents... Instead of sending it to their e-mail address, why not allow them to retrieve it on their Google Drive or Dropbox account ?

## Behavior

The plug-in should be style-agnostic and make use of `a` and `button` elements with a given class, such as `upcloud--google-drive` or `upcloud--dropbox`.

## Development planning

### Sprint 1

- Set up development environment and scaffold project
- Select and set up testing tools
- Test-driven-develop some quick stuff to make sure everything is correct

### Sprint 2

- Code a prototype making use of the [Google Drive API](https://developers.google.com/drive/web/quickstart/quickstart-js)

### Sprint 3

- Refactor, split up the Drive-specific part and set up a proper strategy structure
- Code Dropbox strategy
- Release the kraken

# react-scripts

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.


# CHANGES

This package include a pending pull request [https://github.com/facebook/create-react-app/pull/12091](https://github.com/facebook/create-react-app/pull/12091). This will allow you to have watchOptions for when React is sitting in a remote server like, (WSL, Vgarant, Virtualbox, .etc)

### .env added
```
WDS_POLLING=true
WDS_AGGREGATE_TIMEOUT=200
WDS_POLLING_INTERVAL=1000
WDS_WATCH_IGNORE=**/node_modules
```
## Change to package.json

```
  "scripts": {
    "start": "cloned-react-scripts start",
    "build": "cloned-react-scripts build",
    "test": "cloned-react-scripts test",
    "eject": "cloned-react-scripts eject",
    .../
  }
```
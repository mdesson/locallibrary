# locallibrary
MDN Tutorial for Node + Express

## Running locallibrary

To run in devmode on \*nix systems, use:
```
DEBUG="author,book,bookinstance,genre" npm run devstart
```

On Windows, use:
```
set DEBUG=author,book,bookinstance,genre
```

## Configuring

You must have a config.json in your root directory.

Your Mongoose database user's username and password are stored as `dbuser` and `dbpass`, respectively.
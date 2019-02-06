# locallibrary
MDN Tutorial for Node + Express

## Running locallibrary

To run in devmode on \*nix systems, use:
```
DEBUG=locallibrary:* npm run devstart
```

On Windows, use:
```
SET DEBUG=locallibrary:* & npm run devstart
```

## Configuring

You must have a config.json in your root directory.

Your Mongoose database user's username and password are stored as "user" and "pass", respectively.
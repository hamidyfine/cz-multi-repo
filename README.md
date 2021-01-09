# cz-multi-repo
Use commitizen in multi-repo projects

# Install
`npm install --save-dev cz-multi-repo`

# Usage
Define the script in the `package.json`:
```
...
  "scripts": {
    "commit": "cz"
  }
```
Run the script:
```
npm run commit
```

# Adapter
This package use `cz-conventional-changelog` as the Adapter.

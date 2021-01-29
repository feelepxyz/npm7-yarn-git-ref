# npm7-yarn-git-ref

Using a git reference supported by yarn

```
npm install
```

## Error output from `npm v7.5.0`

```
npm ERR! code 128
npm ERR! command failed
npm ERR! command git clone --mirror -q ssh://git@github.com/Graffino/Browser-Update.git /Users/user/.npm/_cacache/tmp/git-clone-7bb498d7/.git
npm ERR! fatal: destination path '/Users/user/.npm/_cacache/tmp/git-clone-7bb498d7/.git' already exists and is not an empty directory.
```

## Error output from `npm v6.14.11`

```
npm ERR! code 1
npm ERR! Command failed: git checkout 2.0.0
npm ERR! error: pathspec '2.0.0' did not match any file(s) known to git
npm ERR! 
```

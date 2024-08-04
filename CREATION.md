## Use pnpm

This is implemented in the project root. 
This makes developing component packages easier.

```sh
npm install pnpm -g
```

### Create .npmrc 

Create `.npmrc` in the project root.

```
link-workspace-packages = true
prefer-workspace-packages = true
recursive-install = true
```
# perfect-nuxt-js

## Devon's Notes

### VS Code Setup

Correct linting/formatting settings:

```json
{
  "[vue]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  },
  "eslint.format.enable": true,
  "tailwindCSS.emmetCompletions": true,
  "editor.quickSuggestions": {
    "strings": true
  },
  "css.validate": false
}
```

Critical Extensions:

- ESLint
- Headwind
- Tailwind CSS IntelliSense
- Vetur
- Vue 3 Snippets

These steps have already been done in this repo, but in case you want to do create-nuxt-app from scratch:
https://gist.github.com/devmart10/9895822697243605dd6c5f2f98ef0d6d

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

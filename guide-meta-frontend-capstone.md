
`
```sh
git remote add origin https://github.com/tawounfouet/react-littlelemon-meta.git
git branch -M main
git push -u origin main
```
#source : https://create-react-app.dev/docs/deployment/

## Deploy to Github Pages
```sh
#source : https://create-react-app.dev/docs/deployment/


npm install gh-pages --save-dev

```

```json
{
  "homepage": "https://tawounfouet.github.io/react-littlelemon-meta",
  "name": "meta-front-end-developer-capstone",


 "scripts": {
    ...
    ...
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",
    "build": "react-scripts build",
    ..`
  },
  
```

```sh
npm run deploy
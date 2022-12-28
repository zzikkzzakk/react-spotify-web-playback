# Local Demo setup

- In package.json of demo folder:
    - Change dependency of react-spotify-web-playback to local filesystem, i.e. `"react-spotify-web-playback": "file:.."` 
    - Upgrade dependency `"react-scripts": "^5.0.1"`
    - add eslint-config to devDependencies: `"@gilbarbara/eslint-config": "^0.2.4"` 
- In root folder of react-spotify-web-playback: `npm install` 
- In root folder: `npm run build`
- In demo folder: `npm install` 
 

# Testing changes in react-spotify-web-playback
- Change something in react-spotify-web-playback
- Run `npm run build` in root folder twice!! 
- Run `npm start` in demo folder (should be stopped before build!)


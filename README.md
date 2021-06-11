# ark-tamecalc

- yarn create electron-app my-app
- add "electron": "electron ." script in package.json
- rename index.js to main.js, update "main" in package.json
- yarn add react react-dom
- yarn add @types/react @types/react-dom --dev
- add app.js in src
- sort files into renderer, main, and common folders
- add componenets folder into renderer folder
- copy index.js code from index.js in react-electron-boilerplate
- copy app.js code from stardew-bundle-tracker
- in main.js, ensure mainWindow.loadURL(`file://${path.join(__dirname, '../renderer/index.html')}`);

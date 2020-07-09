# ECOleta

## Project
This project was developed during Rocketseat's Next Level Week, in order to become familiar with modern technologies, such as React.

ECOleta is a Web and Mobile Application that helps people find places that collect specific types of waste, such as lightbulbs, batteries, etc.

---
## Technologies

<details>
  <summary>Backend</summary>
  
-   [Node.js](https://nodejs.org/)
-   [Express](https://expressjs.com/)
-   [SQLite3](https://www.sqlite.org/index.html)
-   [Knex](http://knexjs.org/)
-   [Typescript](https://www.typescriptlang.org/)
-   [TS-Node-Dev](https://www.npmjs.com/package/ts-node-dev)
-   [Celebrate](https://github.com/arb/celebrate)
-   [uuidv4](https://www.npmjs.com/package/uuidv4)
-   [Cors](https://www.npmjs.com/package/cors)
-   [Multer](https://www.npmjs.com/package/multer)
-   [ESLint](https://eslint.org/)
-   [Prettier](https://prettier.io/)
-   [VS Code](https://code.visualstudio.com/)
</details>

<details>
  <summary>Frontend</summary>

-   [React](https://pt-br.reactjs.org/)
-   [Typescript](https://www.typescriptlang.org/)
-   [uuidv4](https://www.npmjs.com/package/uuidv4)
-   [Axios](https://www.npmjs.com/package/axios)
-   [React Dropzone](https://github.com/react-dropzone/react-dropzone)
-   [React Icons](https://react-icons.netlify.com/#/)
-   [Leaflet](https://leafletjs.com/)
-   [React Leaflet](https://react-leaflet.js.org/)
-   [ESLint](https://eslint.org/)
-   [Prettier](https://prettier.io/)
-   [VS Code](https://code.visualstudio.com/)

</details>

<details>
  <summary>Mobile</summary>

-   [React](https://pt-br.reactjs.org/)
-   [React Native](https://reactnative.dev/)
-   [Expo](https://expo.io/learn)
-   [Typescript](https://www.typescriptlang.org/)
-   [React Navigation](https://reactnavigation.org/)
-   [Axios](https://www.npmjs.com/package/axios)
-   [Expo Google Fonts](https://github.com/expo/google-fonts)
-   [Expo Location](https://docs.expo.io/versions/latest/sdk/location/)
-   [Expo Mail Composer](https://docs.expo.io/versions/latest/sdk/mail-composer/)
-   [React Native Picker Select](https://www.npmjs.com/package/react-native-picker-select)
-   [ESLint](https://eslint.org/)
-   [Prettier](https://prettier.io/)
-   [VS Code](https://code.visualstudio.com/)

</details>

---
## Setup
### Requirements
To run this application you will need:
  - [Git](https://git-scm.com/)
  - [Node.js](https://nodejs.org/en/)
  - [Yarn](https://yarnpkg.com/)
  - [Expo](https://expo.io/)

1. ### Clone this repository:

```bash
  $ git clone https://github.com/vinisklin/ECOleta.git
```
2. ### Run Back-End

```bash
  # Go into the backend folder
  $ cd server

  # Install the backend dependencies
  $ yarn

  # run migrations
  $ yarn knex:migrate
  # Optional: Add info to backend
  $ yarn knex:seed

  # run api
  $ yarn dev
```

3. ### Front-End

```bash
  # in another tab of the terminal install the frontend dependencies and run it 
  $ cd frontend
  $ yarn
  $ yarn start
```

4. ### Mobile

The Application was developed using **Expo**. It is a free and open source toolchain built around **React Native** to facilitate the process of running and testing applications. [Click here](https://expo.io/learn) to get start with Expo.

```bash
  # in another tab of the terminal, install the dependencies
  cd mobile
  yarn
```

In order to run the application on your device, you need to change the ip config. Go to [api.ts](https://github.com/vinisklin/ECOleta/blob/master/mobile/src/services/api.ts), and replace 192.168.100.49 with your machine's IP.

```javascript
  baseURL: 'http://192.168.100.49:3333', // replace with your IP
```

Now with everything set, run the application

```bash
  yarn start
```

Expo will open a page in your browser, scan the QRcode on the page and wait for the app to load.

---
## License
This project is under the MIT license. See the [LICENSE](https://github.com/vinisklin/ECOleta/blob/master/LICENSE) for more information
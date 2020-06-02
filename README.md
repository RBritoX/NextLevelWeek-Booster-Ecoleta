<h1 align="center">
  <img src="./assets/logo.svg" alt="Ecoleta" width="500">
</h1>

<h3 align="center">
  Index
</h3>

<p align="center">
  ♻️ <a href="#%EF%B8%8F-the-project">The Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  🤖 <a href="#-back-end">Back-End</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  🖥 <a href="#-front-end">Front-End</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  📱 <a href="#-mobile">Mobile</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  🏁 <a href="#-starting-the-project">Starting</a>
</p>

<h3 align="center">
  🚧 In Development 🚧
</h3>

## 🚀 Next Level Week Starter 1

The Next Level Week of [RocketSeat](https://rocketseat.com.br/) came to replace the Omnistack Week, following better for all audiences, from beginners with HTML, CSS and JavaScript, to the most advanced with Node.js, React.js and React Native.

This is version **Booster** of NLW, to check the version **Starter**, access the repository <a href="https://github.com/RBritoX/NextLevelWeek-Starter-Ecoleta">here</a>.

**🎓  Instructor: [Diego Fernandes](https://www.linkedin.com/in/diego-schell-fernandes/)**<br>
**✍🏼  Layout made in [Figma](https://www.figma.com/file/1SxgOMojOB2zYT0Mdk28lB/Ecoleta?node-id=1%3A9) by [Tiago Luchtenberg](https://www.linkedin.com/in/tiago-luchtenberg-0b9a3b97/)**<br>

- [X] **01/06/2020** - Accelerating your evolution (**Introduction**)
- [ ] **02/06/2020** - Looking at opportunities
- [ ] **03/06/2020** - The stack choice
- [ ] **04/06/2020** - Up to 2 years in 2 months
- [ ] **05/06/2020** - My extra

## ♻️ The Project:

The application created in this first edition of NLW, was the **Ecoleta**. An application designed to help people find collection points efficiently.

![Captura de Tela 2020-06-02 às 00 50 43](https://user-images.githubusercontent.com/34657005/83478044-33754200-a46b-11ea-8ebb-0816ed7b2de8.png)

## 🤖 Back-End
The Back-End was developed with Node.js and TypeScript, in API Rest format.
For standardization and organization of the code, ESLint, Prettier and EditorConfig were used.
The connection to the PostgreSQL database was made with DBeaver and Docker to create containers with TypeORM.
For authentication and user access control, JWT (Json Web Token) was used.
To upload images, Multer was used.

### 🛠 Technologies
- **[Node.js](https://nodejs.org/en/)**
- **[TypeScript](https://www.typescriptlang.org/)**
- *[Express](https://expressjs.com/pt-br/)*
- *[Docker](https://www.docker.com/)*
- *[PostgreSQL](https://www.postgresql.org/)*
- *[DBeaver](https://dbeaver.io/)*
- *[TypeORM](https://typeorm.io/#/)*
- *[JWT](https://jwt.io/)*
- *[ESLint](https://eslint.org/)*
- *[Prettier](https://prettier.io/)*
- *[EditorConfig](https://editorconfig.org/)*

## 🖥 Front-End
The Front-End was developed with React.js and TypeScript. For standardization and organization of the code, ESLint, Prettier and EditorConfig were used. The styling was done with Styled-Components. The navigation screens were made with React Router DOM. The validation of login and registration was done with Yup. To connect with the Back-End, Axios was used.

### 🛠 Technologies
- **[React.js](https://reactjs.org/)**
- **[TypeScript](https://www.typescriptlang.org/)**
- *[React Router DOM](https://reacttraining.com/react-router/web/guides/quick-start)*
- *[Styled-Components](https://styled-components.com/)*
- *[React Icons](https://react-icons.netlify.com/#/)*
- *[Polished](https://polished.js.org/)*
- *[Axios](https://nodemon.io/)*
- *[ESLint](https://eslint.org/)*
- *[Prettier](https://prettier.io/)*
- *[EditorConfig](https://editorconfig.org/)*

## 📱 Mobile
The Mobile was developed with React Nativeand TypeScript. For standardization and organization of the code, ESLint, Prettier and EditorConfig were used. The styling was done with Styled-Components. The navigation screens were made with React Navigation. The validation of login and registration was done with Yup. To connect with the Back-End, Axios was used.

### 🛠 Technologies
- **[React Native](https://reactnative.dev/)**
- **[TypeScript](https://www.typescriptlang.org/)**
- *[React Navigation](https://reactnavigation.org/)*
- *[Styled-Components](https://styled-components.com/)*
- *[React-Native-Vector-Icons](https://github.com/oblador/react-native-vector-icons)*
- *[Axios](https://nodemon.io/)*
- *[ESLint](https://eslint.org/)*
- *[Prettier](https://prettier.io/)*
- *[EditorConfig](https://editorconfig.org/)*

## 🏁 Starting the project:

Clone the project: `git clone https://github.com/RBritoX/NextLevelWeek-Booster-Ecoleta`

🤖 To run the **Back-End**, you must first create a container in Docker and a PostgreSQL database in DBeaver. 
<br>Then open the terminal and run the following commands:

````zsh
# to enter the Back-End folder
$ cd backend

# to download the dependencies
$ yarn

# to start the application on port 3333
$ yarn dev:server
````

🖥 To run the **Front-End**, in another terminal tab, execute the following commands:

````zsh
# to enter the Front-End folder
$ cd frontend

# to download the dependencies
$ yarn

# to start the application on port 3000
$ yarn start
````
Now access `http://localhost:3000/`

📱 To run **Mobile**, you need an Android or iOS simulator (Mac only) running on your computer or connect your physical smartphone to USB. To learn how to install / configure, follow the [RocketSeat tutorial](https://react-native.rocketseat.dev/).
<br>Now, on another tab of the terminal, run the following commands:

````zsh
# to enter the Mobile folder
$ cd mobile

# to download the dependencies
$ yarn

# for Android:
# first open the Android emulator
# to start the app on the simulator or on the Android physical smartphone connected to the USB device
$ yarn android

# for iOS:
# to launch the app on the simulator or on the physical iOS smartphone connected to the USB device (only using Mac)
$ yarn ios
````

---

<h3 align="center">
  Made by Raphael Brito (RBritoX)
</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/raphaellbrito/">
    <img alt="React.js version" src="https://img.shields.io/badge/LinkedIn-raphaellbrito-0e76a8?style=flat&logoColor=white&logo=linkedin">
  </a>
  <a href="https://www.facebook.com/RaphaBrito">
    <img alt="React.js version" src="https://img.shields.io/badge/Facebook-RaphaBrito-1778F2?style=flat&logoColor=white&logo=facebook">
  </a>
  <a href="https://www.instagram.com/raphaellbrito/">
    <img alt="React.js version" src="https://img.shields.io/badge/Instagram-@raphaellbrito-833AB4?style=flat&logoColor=white&logo=instagram">
  </a>
</p>

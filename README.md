<div align="center">

# Guess the Champ

![Guess the champ logo image](/assets/images/logo.png)

### A League of Legends gessing game!

[🎮 The project](#-the-project) &emsp;|&emsp;
[🧰 Tech stack](#-tech-stack) &emsp;|&emsp;
[➕ Contributing](#-contributing) &emsp;|&emsp;
[📝 License](#-license) &emsp;

</div>

## 🎮 The project

This is a [League of Legends](https://www.leagueoflegends.com/) guessing game where you have to guess the champions according to their skills (image or description) or synopsis. There is a time limit and every wrong answer will reduce your current score. You can play alone or challenge a friend to a 1v1 realtime match, where the one who guess first wins the game.

`Ps: we are at the first playable alpha so most of the features are not implemented yet...`

![Project main demo image](/assets/images/main-demo-image.png)

You can try the live version here: [guessthechamp.com](https://guessthechamp.com)

## 🧰 Tech stack

### Frontend 🖼

<a href="https://www.typescriptlang.org/">
  <img width="64" height="64" src="/assets/icons/ts.png" alt="Typescript Logo"/>
</a>
<a href="https://reactjs.org/">
  <img width="64" height="64" src="/assets/icons/react.png" alt="React.js logo"/>
</a>
<a href="https://styled-components.com/">
  <img width="64" height="64" src="/assets/icons/styled.png" alt="Styled Components logo"/>
</a>
<a href="https://recoiljs.org/">
  <img width="64" height="64" src="/assets/icons/recoil.png" alt="Recoil logo"/>
</a>
<a href="https://jestjs.io/">
  <img width="64" height="64" src="/assets/icons/jest.png" alt="Jest logo"/>
</a>

<br>

The [frontend](https://github.com/radaelilucca/guess-the-champ-client) was created with [React](https://reactjs.org/), [Typescript](https://www.typescriptlang.org/) and [Styled-Components](https://styled-components.com/) and it's only responsibilities are some anti-cheat logics.</p>

### Backend ⚙️

<a href="https://www.typescriptlang.org/">
  <img width="64" height="64" src="/assets/icons/ts.png" alt="Typescript Logo"/>
</a>
<a href="https://nodejs.org">
  <img width="64" height="64" src="/assets/icons/nodejs.png" alt="Node.js logo"/>
</a>
<a href="https://www.postgresql.org/">
  <img width="64" height="64" src="/assets/icons/postgres.png" alt="Postgresql Logo"/>
</a>
<a href="https://typeorm.io/">
  <img width="64" height="64" src="/assets/icons/typeorm.png" alt="Typeorm logo"/>
</a>
<a href="https://jestjs.io/">
  <img width="64" height="64" src="/assets/icons/jest.png" alt="Jest logo"/>
</a>

<br>

The [backend](https://github.com/radaelilucca/guess-the-champ-server) of course is in charge of all game logics and data persistence, and it was created with [Node.Js](https://nodejs.org), using [express](https://expressjs.com) as the main framework, [postgresql](https://www.postgresql.org/) as the main database and [typeorm](https://typeorm.io/) as the ORM.

Both server and client are using [Typescript](https://www.typescriptlang.org/) as the main programing language and [crypto.js](https://www.npmjs.com/package/crypto-js) to encrypt / decrypt game data in order to prevent cheat through network scans.

<!-- ## Working on it

First of all, you need to clone this repo with the `--recurse-submodules` flag to download the frontend and backend repositories.

```sh

git clone --recurse-submodules @blablabla.git.com

```

### How to run it

🖼 - Frontend:

⚙️ - Backend:

## Building and deploying

🖼 - Frontend:

⚙️ - Backend:

## Testing

🖼 - Frontend:

⚙️ - Backend: -->

## ➕ Contributing

- First of all, leave a star! ⭐️
- Fork this repo
- Create a branch to work on your fix/feature: `git checkout -b feat/my-cool-feature`
- Commit your changes: `git commit -m "feat: add my cool feature"`
- Upload your changes and make a pull request! `git push origin feat/my-cool-feature`

## 📝 License

This project is under the MIT license. See [LICENSE](/LICENSE) file for more details.

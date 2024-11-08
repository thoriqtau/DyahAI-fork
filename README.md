# Generative Image by DyahAI

<p align="center">
  <img src="https://tabella.my.id/static/assets/name.webp" width="50%">
</p>

<p align="justify">
DyahAI is an AI platform that lets users transform ordinary images into unique works of art with customizable styles. Powered by Web3 technology and smart contracts. DyahAI offers a secure, decentralized, and high-quality experience, producing high-resolution images suitable for various needs.
</p>

<img src="https://tabella.my.id/static/assets/grid.webp" />

# Frontend DyahAI
<img src="https://tabella.my.id/static/assets/home.webp" />
<img src="https://tabella.my.id/static/assets/generate.gif" alt="Deskripsi Gambar" />

## 📝 Table of Contents

- [Get Started](#get-started)
  - [Installation](#installation)
  - [Usage](#usage)
- [Contributors](#contribution)

<h2 id="get-started"> 🔗 Get Started</h2>

<h3 id="installation">:hammer: Installation </h3>

Open PowerShell or Windows Command Prompt in administrator mode by right-clicking and selecting "Run as administrator",</br>
enter the wsl --install command, then restart your machine. </br>
[WSL windows installation step](https://learn.microsoft.com/en-us/windows/wsl/install)

```sh
wsl --install
```

Open your WSL, and install dfx.

```sh
sh -ci "$(curl -fsSL https://internetcomputer.org/install.sh)"
```

Next step you can git clone this repository.

```sh
git clone https://github.com/WAW1311/DyahAI
```

Open this project directory.

```sh
cd website
```

Install all required module.

```sh
npm i
```

<h3 id="installation">💡Usage</h3>
Open WSL Ubuntu, start your dfx.

```sh
dfx start --clean --background
```

Deploy this project, If you want to deploy in local.

```sh
dfx deploy
```

if you want to deploy in production :

```sh
dfx deploy --network ic
```
<h3 id="contribution"> Contributors ❤</h3>
<a href="https://github.com/WAW1311/DyahAI/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=WAW1311/DyahAI" />
</a>

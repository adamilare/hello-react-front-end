# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

# 📖 Hello Rails Back-end <a name="about-project"></a>

It is a simple web app built with React, to demonstrate a project setup involving Rails and React implemented as separate applications.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Client</summary>
  <ul>
    <li>React</li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li>Ruby-on-Rails [Back-end](https://github.com/adamilare/hello-react-back-end)</li>
  </ul>
</details>

### Key Features <a name="key-features"></a>

- Displays greetings from API

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.
This app uses API from its back-end counterpart [front-end](https://github.com/adamilare/hello-react-back-end)

### Prerequisites

In order to run this project you need: any web-browser.

### Setup

Clone this project to your desired folder.

```
    git clone https://github.com/adamilare/hello-react-front-end.git
```

### Install

Run from a terminal

```
    cd hello-react-front-end
    npm install
```

### Usage

**To run the project follow the following instruction:-**
you migth have to update the request url in the redux thunk if your server is not running on port '3000'

update the 'greetingsThunk.js' with your server's port.

```
    const { data } = await axios.get('http://127.0.0.1:3000/api/greetings');
```

```
    npm start
```

## 👤 Author <a name="authors"></a>

👤 **Damilare Adepoju**

- GitHub: [@githubhandle](https://github.com/adamilare)
- Twitter: [@twitterhandle](https://twitter.com/mailtodare)
- LinkedIn: [LinkedIn](https://linkedin.com/in/damilareadepoju)
- GitUp Page: [My Page](https://adamilare.github.io/)

## 🔭 Future Features <a name="future-features"></a>

- [ ] Add more API endpoints

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>

If you like this project give a ⭐️.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgments <a name="acknowledgements"></a>

All thanks to Microverse for providing guidance for this project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

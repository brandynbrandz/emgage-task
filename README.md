<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Emgage Task</h3>

  <p align="center">
    A task to to test further knowledge of my skills!
    <br />
    <a href="https://github.com/brandynbrandz/emgage-task"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/brandynbrandz/emgage-task">View Demo</a>
    ·
    <a href="https://github.com/brandynbrandz/emgage-task">Report Abuse</a>
    ·
    <a href="https://github.com/brandynbrandz">Request Demo</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#challenges">Challenges</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

[![Emgage Role Search][product-screenshot]](https://github.com/brandynbrandz/emgage-task)

One of the most interesting challenges undertaken to test my skills.

Here's why:

- The focus was not on UI as in most front-end challenges, but problem solving ability.
- Refreshments of elaticsearch was the main challenging task but manged to handle the challenge.
- The [engage-ui](https://github.com/emgage/engage-ui) is quite good and a bonus, its type-safe.

Of course, the project has not been deployed and but upon request, it will be!

A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With

Some of the frameworks and technologies used in this task are:

- [React](https://reactjs.org)
- [Webpack](https://jquery.com)
- [Redux](https://redux.js.org)
- [Node.js](https://nodejs.org)
- [engage-ui](https://github.com/emgage/engage-ui)
- [ElasticSearch](https://www.elastic.co)

<!-- GETTING STARTED -->

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

##### The project can only be accesed by authorized people

1. Download the zip file and unzip it.
2. Or Clone the repo
   ```sh
   git clone https://github.com/brandynbrandz/emgage-task.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `.env`
   ```JS
   REACT_APP_PORT= 'http://localhost:9200';
   PORT = 9200;
   NODE_ENV = development
   bonsai_url = 'THE ELASTIC SEARCH API'
   ```
5. Run the Node server `node_server.js`
   ```JS
   npm start
   ```
6. Run the React App

   ```JS
   npm run build
   ```

7. Open browser at
   ```sh
   http://127.0.0.1:4000/
   ```
8. Click _Go to Roles_ button and play around with the Type safe implemented code.

<!-- ROADMAP -->

## Roadmap

1. Implemented the backend (`Node.js`)
2. Ensure the component was running without redux implementation.
3. React-redux intergrarion(`store, action, reducers`)
4. Connect redux to the App.
5. Ensure the code is running and cleaning up.

<!-- CHALLENGES -->

## Challenges

- Most of the packages were outdated and brought up some errors while installing new packages that work together.
- Decided to stick with most of the libraries without updated because they were quite a number and in the real world that would mean more resources usage.

<!-- CONTACT -->

## Contact

Your Name - [@brandynbrandz](https://twitter.com/brandynbrandz) - brandynodoyo@example.com

Website: [Brandynodoyo.com](https://brandynodoyo.com)

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

- [Medium](https://medium.com/elasticsearch/introduction-to-elasticsearch-queries-b5ea254bf455)
- [Elastic](https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl.html)
- [Stackoverflow](https://stackoverflow.com/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/brandynodoyo/
[product-screenshot]: ./emgage.jpg

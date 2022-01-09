# MERN+Redux Ecommerce Platform [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

A MERN ecommerce platform with Redux for UI state

## Contents

- [Installation](#installation)
- [Usage](#usage)
- [Questions](#questions)
- [License](#license)

## Installation

First, clone the project and install all the dependencies as follows:

```
git clone https://github.com/baker-ling/ecommerce_platform.git
cd ecommerce_platform
npm install
```

This app relies on MongoDB, which you can run locally or remotely. To use a remote MongoDB, create a `.env` file inside the `ecommerce_platform/server/` and add a line `MONGODB_URI=` followed by the URI for your database.

## Usage


To start the app in developer mode, run the following command in your terminal inside the app's root folder. In this mode, your computer will monitor files in the client-side and server-side folders and recompile / relaunch the server as appropriate.

```
npm run develop
```

You can also seed the database with sample data by running the command `npm run seed` from the root app forlder or the server folder.


To start the app in production mode, run the following commands in your terminal inside the app's root folder.

```
npm run build
npm run start
```



## Questions

If you have any questions, feel free to reach out via one of the following:

- Email: [brian.baker.bdb@gmail.com](mailto:brian.baker.bdb@gmail.com)
- Github: @baker-ling

## License

This application is distributed under the terms of [MIT License](./LICENSE).

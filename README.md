Typescript and Express.js 
=========================

# Note

This repository is actually uses rjmacarthy/express-typescript-starter as a base.
There was an issue regarding routes not working in the parent project so, I fixed those issue and started extending the above repository.

An Express.js project implemented using Typescript with strongly typed objects:

# Installation

Clone the repository

```
npm install 
```

For development:
```
npm run dev
```

To start:
```
npm run start
```

To debug in visual studio code:
```
npm run debug
```

Then run the `launch.json` configuration inside visual studio code `f5`.  You should now be able to set breakpoints in your typescript.

Test
```
npm run test
```

Test Watch
```
npm run test:watch
```

Build to `./dist`
```
npm run build
```

Browse to http://localhost:3000


# Folder structure

```
src/
├── controllers
│   └── index.server.controller.ts
├── helpers
│   └── index.ts
├── index.ts
├── models
│   └── example.model.ts
├── public
│   ├── favicon.ico
│   └── stylesheets
│       └── style.css
├── routes
│   └── index.server.route.ts
├── server
│   └── index.ts
├── socket
│   └── index.ts
├── tsconfig.json
├── var
│   └── config.ts
└── views
    ├── error.pug
    ├── index.pug
    └── layout.pug
```

# Docker

Run the image `docker-compose up`

Open `http://localhost:8080`


# License

MIT


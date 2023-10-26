# react-sample-app

React Sample Application

## Application purpose

React sample application purpose is to help bootstrap new React projects in a simple and fast way. This application can also be considered a boilerplate application with all the preferred development configurations, folder structure and tools in place and ready to start coding.

Please, bear in mind that this application is always evolving and new tools may be added along the way.

## Application Tech Stack

-   `React` framework (with Typescript) for the overall application development;
-   `Typescript` coding language;
-   `SASS` style pre-processor to build the needed application styles;
-   `Axios` to communicate with the backend API;
-   `DotEnv` to load project environment variables;
-   `PicniCSS` lightweight CSS framework for UI styling;

## Application Support tools

-   `Prettier` for code formatting;
-   `Webpack` to bundle the application and serve it in development mode;
-   `Log4Brains` to manage Architectural Decision Record (ADR) and generate static HTML knowledge base;
-   `Statoscope` to generate reports about the application;

## Application Testing tools

-   `Jest` javascript testing framework;
-   `React Testing Library` testing framework for working with React components;

## Application scripts

### Installation and application bootstrap

From the project root folder, please execute the following commands in a terminal window:

```bash
# install the application dependencies
npm i

# start the application in development mode
npm start
# or
npm run dev

# build a version of the application for distribution
npm run build
```

### Testing

```bash
# run the application unit tests
npm run test

# run the application unit tests and present a code coverage report
npm run test:coverage
```

### Architecture Decisions Record (ADR)

```bash
# add a new entry to the application ADR
npm run adr:add

# serve the application ADR for consulting in a browser
npm run adr:serve
```

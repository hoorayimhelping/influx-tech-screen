# InfluxData UI Team Technical Interview

Hello! This is a skeleton app used for InfluxData's UI Dumplings Team's technical interview.

The purpose of this interview is to determine your technical ability with React and JavaScript and your communication skills. This interview will attempt to assess your ability to structure and organize an app, your ability to write reusable and maintainable React and JavaScript code, and your ability to communicate your thoughts, both verbally and in code.

## Interview Question:

Using the supplied mock data located in `src/mock_data.json` (a JSON array of 35 items of somewhat arbitrary shape representing purchasing history), build a front-end experience using React and general purpose JavaScript. The front-end application should meet the following criteria:

- The main display is a table. This table should display 35 rows of columns (i.e. the entire JSON array)

- The columns should be as follows:
  - User's full name
  - Total items purchased by that user
  - The user's most expensive item
  - A human readable date based on the timestamp

- The table by default should be sorted alphabetically by user's last name. In other words, last names starting with A, B, C should come before names starting with X, Y, Z.

- The table should be sortable by the four columns (User's name, total items purchased, most expensive item, and date), both ASC and DESC.

### General information
- Some simple table CSS has been supplied
- The app uses create-react-app, which comes with a json loader. This allows you to import the json file like any other module.
- Clone this app from github, then run `npm start` to fire it up

Good luck, have fun (GLHF)!

---

## Create React APP

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

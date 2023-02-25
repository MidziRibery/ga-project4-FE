# Muslim Mastery

This is a MERN stack web application created for General Assembly’s Software Engineering Immersive Program. This is the frontend repository of the application. The backend repository can be found [here](https://github.com/MidziRibery/ga-project4-BE).

Muslim Mastery is the one-stop Social Media place where students and teachers align their intentions in knowledge seeking and mastering them! The platform aims to serve two set of users: Teachers and Students. It helps build the bridge over the gap between providers and seekers of the Islamic knowledge. Teachers can upload their profiles and share what they can offer specifically, while students who are hungry for knowledge, or have dependents who need help with their education, can safely access the platform to find a teacher that fit their needs. By consolidating the specific needs, this platform offers a niche solution to an ever growing demand. Users can also leave comments or ratings of their experience which will increase the quality of performance of the teachers.

### Technical Used

These are the tools that helped made the application possible =>

Frontend:

- [React](https://reactjs.org/)
- [React Router](https://reactrouter.com/en/main)
- [React Dropzone](https://react-dropzone.js.org/)
- [Styled Components](https://styled-components.com/)
- [Material UI Icons](https://mui.com/material-ui/material-icons/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [Redux Persist](https://www.npmjs.com/package/redux-persist)
- [Formik](https://formik.org/)
- [Yup](https://www.npmjs.com/package/yup)

Backend:

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [Mongoose](https://mongoosejs.com/)
- [JWT Token](https://jwt.io/)
- [Multer](https://www.npmjs.com/package/multer)

Database:

- [MongoDB](https://www.mongodb.com/home)

### Installation Instructions

All the necessary libraries needed for the web application to run are found in the package.json file provided. Install them using <code>npm install</code> if you are using node package manager.

If you wish to run the backend server with your own database, you will need to link your database to the server for it to run properly.

## Development Process

### User Stories

Firstly, the important features of the web application were determined having these user stories in mind:

    User Story 1: It is not easy to find credible Teachers to teach the Islamic Knowledge that can cater to my specific needs such as location, availability, and platform.
    User Story 2: As a teacher, I want to expand my clientele without the need to spend money on advertisements. As most social media platform is very wide, there is no niche solution.

From there, these are some of the main features that our web application should have:

- Platform where teachers and student identify themselves and share more background information about what they can provide and their needs by registering
- Function to add friends
- Function to allow users to comment, upload media and post.
- Function to allow users to like comments and posts.

### Wireframes

Simple wireframes were then developed to accommodate to all the features the application should have:

![Login Page Wireframe]

![Home Page Wireframe]

![Profile Page Wireframe]

### Server Routes

### Problems Encountered

### Future Development

- To have separate forms for teachers and students.
  - To make the registration for teachers stricter, by asking them to upload certifications before enabling them to proceed with registering.
  - To break down the components of the form further, so we can pick up specific data, consolidate them and add to search functions and tags.
- To add an admin dashboard to moderate the comments and contents of posts and profiles, as well as to process the registration.
  - Allow admin to make changes to the video, not just deleting them

# Getting Started with Create React App

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

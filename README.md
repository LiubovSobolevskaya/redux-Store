# Redux Store

17th Assignment of UCB Extension Web Development Bootcamp.<br>
Please visit the deployed [website](https://redux-shop-luba.herokuapp.com/).

## Description

This web application is an e-commerce platform that provides users with a seamless online shopping experience. The application utilizes Redux as the primary method for managing global state. 

To access the Redux store, the React front end utilizes a Redux provider. This provider component wraps the entire application and allows all components to connect to the Redux store, gaining access to the application's global state.

Changes to the global state are determined through reducers, which are passed to the Redux store. These reducers define how the state should be updated in response to dispatched actions. By using Redux, the application benefits from a predictable state management flow, allowing for efficient and controlled state updates.

To extract specific data from the Redux store, the application relies on Redux's mechanisms. It utilizes selectors or mapStateToProps functions to retrieve the required state data from the global store. This approach ensures that components can access the necessary data without directly interacting with the Redux store.

When it comes to dispatching actions, the application relies on Redux's dispatch mechanism. Actions are dispatched to the Redux store, triggering the appropriate reducers to update the global state accordingly. This enables the application to handle user interactions, API responses, and other events in a centralized and organized manner.

Overall, the web application has chosen to leverage Redux for global state management, providing a reliable and scalable solution for handling complex state interactions. By utilizing Redux instead of the Context API, the application benefits from a mature and widely adopted library that offers robust tools for managing state in a predictable and efficient manner.

## Requirements
```
npm run install
npm run seed
npm run develop
```

---

## Technology Used

- [Git](https://git-scm.com/)
- [JavaScript](https://www.javascript.com/)
- [Node.js](https://nodejs.dev/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://www.npmjs.com/package/mongoose)
- [React](https://react.dev/)
- [GraphQL](https://graphql.org/)
- [Redux](https://redux.js.org/)

## Author Info

### Liubov Sobolevskaya

- [LinkedIn](https://www.linkedin.com/in/liubov-sobolevskaya/)
- [Github](https://github.com/LiubovSobolevskaya)
- [Kaggle](https://www.kaggle.com/lyubovsobolevskaya)


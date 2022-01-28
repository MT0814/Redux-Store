# 22 State Homework: Redux Store

## Description

Managed global state by using React’s Context API. The Context API is quickly gaining traction as a worthy alternative or perhaps even successor to other libraries that manage global state in tandem with React, such as Flux or MobX. Nonetheless, the open source JavaScript library Redux remains the industry standard for managing complex state in a large-scale React application, and you’ll likely encounter it on the job.

Refactored the e-commerce platform from [Activity 26](../01-Activities/26-Stu_Actions-Reducers/Unsolved) so that it uses [Redux](https://redux.js.org/). You won’t need to make sweeping changes to the code, but you will need to read through the Redux documentation on your own to find the information you need. Some guidelines have been provided in the Getting Started section to point you in the right direction.

## User Story

```md
AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem
```

## Acceptance Criteria

```md
GIVEN an e-commerce platform that uses Redux to manage global state
WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the Context API
WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
WHEN I review the way the app determines changes to its global state
THEN I find that the app passes reducers to a Redux store instead of using the Context API
WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API
```

## Mock-Up

This section reviews the web application's general appearance and functionality.

The following animation shows how a user can register using the Signup page and then navigate to the Products page:

![A user registers on the Signup page and then navigates to the Products page, which displays images and descriptions of products.](./Assets/22-state-homework-demo-01.gif)

The following animation shows how the user can select a category, choose a product, view details about it on the product page, and add and remove it from their shopping cart:

![The user selects a category, chooses a product, views details about it on the product page, and adds it to and removes it from their shopping cart.](./Assets/22-state-homework-demo-02.gif)

Finally, the user can check out by going to their shopping cart, as shown in the following animation:

![The user checks out by going to their shopping cart.](./Assets/22-state-homework-demo-03.gif)

## Technology used

Added Redux to this application, refer to the [Redux Fundamentals basic tutorial](https://redux.js.org/basics/basic-tutorial).

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Website Screenshots

![screenshot](./Assets/shop.png)

Please click [here](https://shopshop-mt.herokuapp.com//) for the Shop app.

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.

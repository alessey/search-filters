# Search Filters Interview Exercise

The goal of this exercise is to design and implement a configurable search UI.

Integrate with the `useQuery` hook as a mock data source. The data returned by this hook should be used to construct the `<SearchFilters />` component, which will allow users to apply additional filtering to their search query. The `type` attribute returned for each filter object should guide your choice of UI element.

- `oneOf` should restrict the users to a single selection
- `many` should allow users to select 0 or many of the options provided

[Gestalt](https://gestalt.netlify.app/) (a UI library from Pinterest) is included as a dependency and should be leveraged to help speed up development time. Please refer to the [Gestalt Documentation](https://gestalt.netlify.app/) for available components and their configurable props.


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Setup

To get started with development, clone this repo and run the following commands in the project dir:

Install the project dependencies with:

`npm i`

Start the app in development mode:

`npm start`

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

# Step 1:
### Create React App

[Create React App](https://github.com/facebookincubator/create-react-app)  is a comfortable environment for  **learning React**, and is the best way to start building  **a new  [single-page](https://reactjs.org/docs/glossary.html#single-page-application)  application**  in React.

It sets up your development environment so that you can use the latest JavaScript features, provides a nice developer experience, and optimizes your app for production. You’ll need to have  [Node >= 14.0.0 and npm >= 5.6](https://nodejs.org/en/)  on your machine. To create a project, run:

```
npx create-react-app my-app
cd my-app
npm start
```
[Create React App Reference](https://reactjs.org/docs/create-a-new-react-app.html)

```
npx create-react-app my-app --template typescript
```
[Create React App Typescript Reference](https://create-react-app.dev/docs/adding-typescript/)

# Step 2:
Components
- app (layout, header)
- pages (error, login)

# Step 3:
```
npm i react-router-dom
```
```
import { BrowserRouter as Router, Route, Routes, Navigate } from 'react-router-dom';
```
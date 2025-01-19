# First Lesson


#### Install React
* you should install node and npm
* You can use vite
    * **Vite** is a very fast and customizable modern tool that aims to provide a linear development experience for modern web projects. You can use it to create your React apps in a fast and reliable way. It also has the same features as create-react-app (CRA).
  ````
  npm install vite
  npm create vite@lastest
  ````
  * or you can use simple react install:
  ````
  npx create-react-app [prject name]
  ````
  
#### To run the project:
````
npm start
````

#### if you faced the next issue
````
Module not found: Error: Can't resolve 'web-vitals' 
in '/project-path/first-look/src'
````
#### then installing the next package will solve the issue:
````
npm install --save-dev web-vitals
````
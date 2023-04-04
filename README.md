#### This App
- It is not the full a app where we learn everything from scratch it requires pre-requisites This is an Advance Course not for beginners
- Should be familiar with the react and node fundamentals because 
"When it comes to MERN its really about combining our existing knowledge of frontend and server instead starting everything from the blank page
- React basic knowledge of the components and React hooks and how to implement those hooks in the app Like - ( useState , useEffect , useMemo , useReducer , useContext and local and how to create Global Context and Local context )
- Nodejs/Express - how use api calls how to create basic server , how to connect server , Basic server , Can Create Controllers ,and  Routes , MongoDB Atlas - account and know how to connect to it , JWT - some experience with json web tokens.

#### Free Resources
If you need to brush up on React or Node/Express fundamentals, feel free to reference the following videos :



React Fundamentals

Node/Express Fundamentals

Node/Express - MongoDB, Atlas, JWT

Or you can enroll in my React or Node.js courses where we cover more complex topics as well.

BUT THE ENROLLMENT IS NOT REQUIRED FOR THIS COURSE!!!

#### You will have to learn basics of the react , node and mongodb
follow the youtube of either one of the sources for learning it 
#### for javascript 
- from code with harry 28 
- from the john smilga - udemy 46 hr with the projects - on yt 15 projects in 10 hr 
- from technical thapa - 16 basic to advance javascript concept 
- from the jonas sch - 20 hr content from basic to advance udemy course 

#### for the mern stack
- code with harry node , express , mongodb - 2hr each 
- 6 pack programmer react 3hr , node , express , and mongodb 1-1:30 hr courses - requires basic knowledge of the javascript.
- john smilga - node 20hr course on udemy 40hr , react 12hr course on udemy 67hr , javascript course on udemy 46 hr, mongodb course included in the node js course ( this is for the basic to advance level with bunch of projects ) 



## Jobify  App

###### Setup React App

- create 'client' folder
- open terminal
- cd client
- npm create-react-app . If get error because of the version like don't support it then npm create-react-app@latest projectname command instead
- npm start - to run the dev server
- set editor/browser side by side
- copy/paste assets from complete project 


#### Spring Cleaning
cleaning the css pre-build files from the source files - learn how to style in different videos we won't going to write css in the whole course
- in src remove
- App.css
- App.test.js
- logo.svg
- reportWebVitals.js
- setupTests.js
- fix App.js and index.js


#### Title and Favicon

- change title in public/index.html
- replace favicon.ico in public
- resource (favicons)[https://favicon.io/]


#### Normalize.css and Global Styles 
normalize is just to write margin , padding and box-sizing in fancy way
global style for applying for every element to have a same style

- CSS in js - 
personal notes
how to define the variable or watermark color in css

:root{
    double dash to start and then the variable name you want to provide and then the property
  --mybg:  blue;
}

to use in code
the parameter to target and then in the brackets the property want to apply to and then the var variable access and then the variable name in the (variable name) in these in our case --mybg
syntax in 
:root{
    --variablename: value in css the styling;
}

// to access it
body{
    property to apply to : var(variable name);
}

eg- 
:root{
    --bg-color: red;
}

body{
    background-color: var(--bg-color);
}


- saves times on the setup
- less lines of css
- speeds up the development process
- normalize.css
- small css file that provides cross-browser consistency in the default styling of HTML elements.
- (normalize) [https://necolas.github.io/normalize.css/] - to learn more about normalize css
- npm install normalize.css
- import 'normalize.css' in index.js - import it before index.css 
"because on our global style we will be relying on our normalize one"
- SET BEFORE 'index.css'
- if any questions about normalize or specific styles
- coding addict (Default Starter) [https://youtu.be/UDdyGNlqK5w] - video covering the normalize and specific styling in depth
- Repo (Default Starter ) [https://github.com/john-smilga/] 

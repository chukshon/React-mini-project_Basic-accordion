Hey! I'm on a mission to learn react. I'll be posting series of mini-react projects likes this regularly.


# React-mini-project_Basic-accordion
This is a basic accordion app where we have a list of questions and we can toggle the answers also as the user toggles the answer the icon changes inside the button,This was built with React, Html and CSS. 

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Below you will find some information on how to perform common tasks.<br>


## Prerequisites

Before you begin, ensure you have met the following requirements:

* [Git](https://git-scm.com/downloads "Download Git") must be installed on your operating system.

## Installing

To install, follow these steps:

Linux and macOS:

```bash
sudo git clone https://github.com/chukshon/React-mini-project_Basic-accordion.git
```

Windows:

```bash
git clone https://github.com/chukshon/React-mini-project_Basic-accordion.git
```

After creation, your project should look like this:

```
React-mini-project_Basic-accordion/
  node_modules/
  public/
    index.html
    favicon.ico
    logo192.png
    logo512.png
    manifest.json
    robots.txt
  src/
    App.js
    data.js
    index.css
    index.js
    Question.js
  package-lock.json
  package.json
  README.md
```

For the project to build, **these files must exist with exact filenames**:

* `public/index.html` is the page template;
* `src/index.js` is the JavaScript entry point




## Available Scripts

In the project directory, you can run:

### `npm install`
This command installs a package and any packages that it depends on. If the package has a package-lock;

#### React Icons

[react icons](https://react-icons.github.io/react-icons/)

```How to use
import { FaHome } from 'react-icons/fa';
const Component = () => {
  return <FaHome className='icon'></FaHome>;
};
```

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
The page will reload if you make edits.<br>
You will also see any lint errors in the console.


### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!


## License

This project is **free to use** and does not contains any license.

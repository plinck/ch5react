# ch5react

## This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

This project used the cra-template-ch5-typescript starter template by Chris Poole, AVSP Ltd.  Many thanks to Chris for doing the heavy lifting on getting started with react and ch5

This project has been updated to change the file structure around a but to more fit the structure I typically used.  I have also copied the react-ch5 code into my project so I can manipualet it on my own and inetgrate it based on my style.  I also got rid of yarn since I dont use it and I had issues with it messing up my gcloud CLI and firebase CLI.  Certainly ths is my issue but I am not in the mood to switch to yarn yet.

My goal is to convert it to use JSON simulator as a simpler way for me to get stafrted without using a x60 series touchpanel snd processor.s

## Crestron CH5 Specific

In the top of App.tsx, enter your development machine's IP address or hostname.

A demodir SMW for your processor is in the smw folder.

`npm build` will compile the code in src to the build directory.
`npm build:archive` will build a ch5z file from the most recently built build and output to the dist folder.
`npm build:deploy` will deploy the ch5z from the dist folder to a touchpanel "panel".

`npm build:onestep` will execute the above three steps in sequence.

Once the panel is deployed, you can use `npm start` then click the link to your development machine to get live reloading.

Any questions? Drop me a line on github or chris@avsp.co.uk

## Available Scripts

In the project `client` directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

# Steaming App built with React


<p align="center">

   ![Visual Studio Code](https://img.shields.io/badge/-VS%20Code-blueviolet?style=for-the-badge&logo=visualstudiocode)
![ReactJS](https://img.shields.io/badge/-React-informational?style=for-the-badge&logo=react)
![Javascript](https://img.shields.io/badge/-JavaScript-critical?style=for-the-badge&logo=JAVASCRIPT)
![Redux](https://img.shields.io/badge/-Redux-purple?style=for-the-badge&logo=redux)

</p>

<br/>
<br/>

## Description
### Are you the next big streamer? Then streamy is just the app for YOU! Stream all you want to your fanbase.

<br/>

## Setup

You need to have 3 Terminals open. <br/>
Run <b>yarn start/npm start</b>t in the client, api and rtmpserver folders.

<br/>

### Packages Used:
Ensure that that you have the following installed in the client directory:
* React
* React-Redux
* React Final Form
* FLV.JS
* Node Media Server
* JSON Server

<br/>

Use OBS to stream. To setup OBS for streaming ensure that you create a 'Scene' with Audio Input and Display Capture. Go to Settings > Stream then set Service to custom and paste rtmp://localhost/live in the server section and a Stream Key of 1(this means that the stream will be displayed when you select the first item).

<br/>

## ScreenShots

<p float="left">
  <img src="page_one.jpg" width="500">
  &nbsp;&nbsp;
  <img src="page_two.jpg" width="500">
  &nbsp;&nbsp;
  <img src="page_three.jpg" width="500">
  &nbsp;&nbsp;
  <h3>Active Stream</h3>
  <img src="page_four.jpg" width="500">
  &nbsp;&nbsp;
  <h3>Inactive Stream</h3>
  <img src="page_five.jpg" width="500">
</p>



<br/>

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.
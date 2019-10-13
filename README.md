# The stack
* Electron
* React - Create React App
* Rescripts
* Electron Builder

Electron is a framework for creating native applications with web technologies like JavaScript, HTML, and CSS. In our case we'll be using React.

React is JavaScript library for building user interfaces... and so much more.

To make the React setup easier we're going to use Create React App. Create React App (CRA) is awesome because it saves buckets-of-time and eliminates config hell.

Create React App is a tool (built by developers at Facebook) that gives you a massive head start when building React apps. It saves you from time-consuming setup and configuration. You simply run one command and Create React App sets up the tools you need to start your React project.

Rescripts allows us to customize the CRA setup without ejecting.

Ejecting CRA is something you really want to avoid, because you will no longer benefit from the future improvements to CRA.

Electron Builder is used to package our desktop app for distribution.


```
yarn electron-pack
```
You will see the packaged artifacts under the dist directory.

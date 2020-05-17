<h1 align="center">Video call with NodeJS</h1>

This project implements WEB video calls using [WebRTC](https://webrtc.org), a technology focused on real-time communication via browser or native app.

<p align="center">
	<img src="https://user-images.githubusercontent.com/54327441/82153287-e83d1b80-983c-11ea-8d6e-cb3ab11aaf07.png" height="250" width="458" alt="Demo screen" />
</p>


<h2>Environment requirements</h2>

- [NodeJS](https://nodejs.org) with the [NPM](https://www.npmjs.com) package manager installed.
- Install the [Yarn](https://yarnpkg.com) if you prefer to use it.

<h2>Required NPM packages</h2>

|  Módulo    | Objetivo                                                  |
| -------------------------: | ----------------------------------------- |
| `Express`  | Create a web server to serve statically the test page     |
| `SocketIO` | Synchronizes events between callers                       |


<h2>Features</h2>

- Video and audio stream
- Auto-start call
- End the call
- Shared text area, updated on all callers in real-time


<h2>Get started</h2>

- Clone the project: `git clone https://github.com/felipeleite11/video-call.git`
- Execute instalation of dependencies: `npm install` ou `yarn`
- Execute application: `npm start` ou `yarn start`
- Open `http://localhost:3000/room_name` in your browser
- **Allow the required permission** to access your **camera** and **microphone**
- Open a anonymous instance of your browser and open the **same URL**
- Allow the required permissions again


<h2>The expected is...</h2>

- Two identical images, side by side, captured directly from your webcam
- When speaking into your microphone, your voice should be echoed through your device’s speaker


<h2>Browser compatibility</h2>

WebRTC project is compatible with most desktop and mobile browsers.

- [X] Chrome
- [X] Firefox
- [X] Edge
- [X] Safari
- [X] Opera
- [ ] Internet Explorer

Check more support details in [Can I use](https://caniuse.com/#search=webrtc).


<h2>Contribution suggestions</h2>

- Test page styling
- Call start from a button
- Allow room creation
- Improve responsiveness for mobile devices
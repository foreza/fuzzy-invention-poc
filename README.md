# What is this?

- A quick POC demonstrating LiveRamp ATS.js capabilities for video players.
- This allows you to retrieve envelopes (with an encrypted rampID) to send to LiveRamp SideCar enabled providers for decrypting/targeting.
- The injected snippet source is here: https://foreza.github.io/fuzzy-invention-poc/player-iframe-example.html

## Instructions
Go to any ATS.js enabled website (type `ats` and see what comes up), open the console, and try the following:

```js
var testVideoPlayerIframe = document.createElement('iframe');
testVideoPlayerIframe.src = "https://foreza.github.io/fuzzy-invention-poc/player-iframe-example.html"
testVideoPlayerIframe.id = "frameExample"
testVideoPlayerIframe.style = "position: absolute; right: 0; bottom: 0; height: 500px; width: 500px;"
document.body.appendChild(testVideoPlayerIframe);
```
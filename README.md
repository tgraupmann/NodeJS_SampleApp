# `Node.js` Chroma Animation Sample App

**Table of Contents**

* [See Also](#see-also)
* [About](#about)

<a name="see-also"></a>
## See Also

**Docs:**

- [Chroma Animation Guide](http://chroma.razer.com/ChromaGuide/) - Visual examples of the Chroma Animation API methods

**Apps:**

- [ChromaClientForDiscord](https://github.com/tgraupmann/ChromaDiscordApp) - Add Chroma lighting to the Discord App events

- [ChromaClientForMixer](https://github.com/tgraupmann/ChromaClientForMixer) - Add Chroma lighting to the Mixer streaming experience

- [ChromaClientForTwitch](https://github.com/tgraupmann/ChromaTwitchExtension) - Add Chroma lighting to the Twitch streaming experience

**Plugins:**

- [CChromaEditor](https://github.com/RazerOfficial/CChromaEditor) - C++ native MFC library for playing and editing Chroma animations

- [GameMakerChromaExtension](https://github.com/RazerOfficial/GameMakerChromaExtension) - GameMaker extension to control lighting for Razer Chroma

- [HTML5ChromaSDK](https://github.com/RazerOfficial/HTML5ChromaSDK) - JavaScript library for playing Chroma animations

- [UE4_XDK_SampleApp](https://github.com/razerofficial/UE4_XDK_SampleApp) - UE4 Chroma samples and runtime module with Blueprint library for the ChromaSDK

- [UnityNativeChromaSDK](https://github.com/RazerOfficial/UnityNativeChromaSDK) - Unity native library for the ChromaSDK

<a name="about"></a>
## About

The `Node.JS Sample App` is a `Node.js` console app that shows the animations from the [Chroma Animation Guide](http://chroma.razer.com/ChromaGuide/).

**Screenshot:**

![image_1](/images/image_1.png)

## Setup

### Node.js

* Install the latest [Node.js](https://nodejs.org/en/)

### Nodemon

Nodemon is useful to auto relaunch after changes to the script.

* To install `nodemon`.

```
npm install nodemon -g
```

### Python

* Install [Python 3.X](https://www.python.org/downloads/) for the C++ interface

* Set the `PYTHON` environment variable to the Python install path.

```
%USERPROFILE%\AppData\Local\Programs\Python\Python38-32\python.exe
```

## Launch

To launch the sample in the terminal with `node`.

```
node app.js
```

To launch the sample in the terminal with `nodemon`.

```
nodemon app.js --no-stdin
```

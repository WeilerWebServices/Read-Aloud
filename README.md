
<div align="center">
	<img src="img/icon.png" width="128" height="128">
	<br>
	<img src="docs/images/logo-text-trans.png" width="391" height="66">
	<br>
	A <b>Text to Speech Voice Reader</b> extension for your browser!
</div>

## Overview
Read Aloud is a Chrome and Firefox extension that uses text-to-speech technology to convert webpage text to audio.&nbsp; It works on a variety of websites, including news sites, blogs, fan fiction, publications, textbooks, school and class websites, online universities and course materials.

Read Aloud is aimed at users who prefer to listen to content instead of reading, people with dyslexia or other learning disabilities, children learning to read, or simply to provide users with alternative way to consume web content.

Read Aloud allows you to select from a variety of text-to-speech voices, including those provided natively by the browser, as well as by text-to-speech cloud service providers such as Google Wavenet, Amazon Polly, IBM Watson, and Microsoft.&nbsp; Some of the cloud-based voices may require additional in-app purchase to enable.

## Basic Usage

### Extension Button
<img src="docs/images/demo-extension-button.gif">

### Right Click Menu
<img src="docs/images/demo-right-click.gif">


## Advanced Usage

### Shortcuts

```yaml
ALT-P           : Play/Pause
ALT-O           : Stop
ALT-Comma       : Rewind
ALT-Period      : Forward
```

### Customization

You can change the voice, reading speed, pitch, or enable text highlighting:

1. Click the Read Aloud icon on the [Extensions menu](https://i.imgur.com/KTqFZ3Q.png).
2. Stop any text that may be playing.
3. Click on the Gear icon in the Read Aloud context menu. (It may take a second or two for settings to appear)


### Using Premium Voices
[Using Premium Voices (Google Wavenet & Amazon Polly)](docs/usage/premium-voices.md)


## Installation

### Chrome and Chromium-based browsers
You can get the latest available Read Aloud Extension version from the [Chrome Web Store](https://chrome.google.com/webstore/detail/read-aloud-a-text-to-spee/hdhinadidafjejdhmfkjgnolgimiaplp).

### Firefox
You can get the latest version of Read Aloud Extension from the [Mozilla Add-ons website](https://addons.mozilla.org/en-US/firefox/addon/read-aloud/).

#### Firefox install from source

1. Create a build directory with `mkdir build`
2. Run `npm run-script package`
3. Extract the resulting zip file. You should see a `manifest.json` which will be used later.
4. In Firefox, first make sure there isn't an existing read-aloud add-on already installed
5. type `about:debugging` in the Address bar and enter.
6. Click on "This Firefox" then click "Load Unpackaged Extension"
7. Select the `manifest.json` file produced earlier.

---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: general
---


<div class="bg-light-purple tc">
<div class="f2 tracked measure-wide dib tl" markdown="1">
Electron Workshop
</div>
</div>

<div class="bg-light-purple tc pb4">
<div class="f5 measure-wide dib tl" markdown="1">
<div class="tc">
  <div>Sunday Nov 1, 2017</div>
  <div>9am - 6pm</div>
  <div>at <a href="#">General Assembly</a> (~Farragut area)</div>
  <div>Lunch Provided</div>
</div>
</div>
</div>

<div class="bg-light-green pa5-ns tc">
<div class="measure-wide dib tl" markdown="1">
### Workshop Description
[Electron](https://electron.atom.io/) is a framework you can use to make desktop applications using javascript. You may have already used an Electron app if you have the Slack app or the text editor Atom. With electron, making a simple desktop application is as easy as making a simple web application. Learn to make your own Electron app in this 2-3 hour workshop :D

Electron provides a set of [cross-platform APIs](https://github.com/electron/electron-api-demos) you can use to interact with the desktop computer. You can use these to have an icon in the tray/menubar, to display notifications, register keyboard shortcuts, and much more. An Electron application has a node “server” running locally doing most of the work, and often additionally a browser process running locally to display things prettily.

No node experience required, but basic javascript experience would be helpful. If you want to play with Node ahead of time anyway (or brush up on your Javascript), I'd recommend NodeSchool's two command-line courses: [Javascripting](https://github.com/workshopper/javascripting) and [LearnYouNode](https://github.com/workshopper/learnyounode). If you'd enjoy reading/skimming a book, I might recommend [Eloquent Javascript](http://eloquentjavascript.net/) (free to read online).
</div>
</div>

<div class="bg-light-purple pa5-ns tc">
<div class="measure-wide dib tl" markdown="1">
### Scenario / User Story
You work remotely. When pair programming or video chatting online, sometimes the connection gets bad.
You're never sure if it's your side or their side having issues.
Sometimes you smartly have a terminal open and have `ping google.com` running - then you can tell whether your connection is good!
You'd love it if:

1. You could tell at a glance (without an additional terminal window) whether your ping is currently good or bad
2. You could get a notification when your wifi goes out, or comes back
</div>
</div>

<div class="bg-light-green pa5-ns tc">
<div class="measure-wide dib tl" markdown="1">
### Our Project
In this workshop, you will create from start to finish a tray icon that will display whether or not you are currently connected to the internet. A node process inside of the Electron app will ping google.com every second. We will then:

1. Use the tray api to change the app’s icon to reflect the current state
2. Display a notification when the internet appears to go up or down

You can see two example applications like this, here:

- https://github.com/groeneveld/am-i-connected
- https://github.com/caseywatts/electron-ping

And an unrelated application that I've written:

- https://github.com/caseywatts/heroku-ci-menubar

### Resource Intensity
An electron menubar app uses RAM and CPU resources comparable to other menubar apps.

Casey's electron app `electron-ping` uses this amount of CPU and RAM to run:
- 0.9% CPU, 70.6 MB of RAM

Spot-checks of some other menubar apps running in the background:
- Dropbox 0.3% CPU, 165MB
- Screenhero 0.2% CPU, 124MB
- Google Drive 0.3% CPU, 151MB

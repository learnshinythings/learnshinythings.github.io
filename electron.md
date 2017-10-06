---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: general
---


<div class="bg-purp tc">
<div class="f2 tracked measure-wide dib tl" markdown="1">
Electron Workshop
</div>
</div>


<div class="bg-purp-light pa4-ns tc">
<div class="measure-wide dib tl" markdown="1">
  [Electron](https://electron.atom.io/) is a framework you can use to make desktop applications using JavaScript. You may have already used an Electron app if you have the Slack app or the text editor Atom. With Electron, making a simple desktop application is as easy as making a simple web application.

  <div class="flex items-center justify-center mt4">
    <img src="/class-photo-banner.png" class="banner">
  </div>

  In this one-day workshop, you'll use modern javascript (ES2017) to make an Electron menubar app that will help you understand how reliable your current wifi connection is. You'll use desktop notifications, a menubar icon, and global hotkeys.

  <div class="flex flex-column items-center justify-center mt4">
    <div class="tc pa3 ma3 ba br4 b--purple bg-purp-light">
      <div>Sunday Nov 12, 2017</div>
      <div>10am - 5pm</div>
      <div>at <a href="https://generalassemb.ly/locations/washington-dc" class="link">General Assembly</a> (~Farragut area)</div>
      <div>$100 for the 8 hour class</div>
      <div>Lunch Included</div>
    </div>

    <a href="https://ti.to/learn-shiny-things/learn-electron" class="link ma3">
      <div class="tc pa3 ba br4 b--purple bg-purp shadow-3">
        Register Interest or Sign Up
      </div>
    </a>
  </div>
</div>
</div>


<div class="bg-purp pa5-ns tc flex items-center justify-center">
<div class="dib tl" markdown="1">

## The Teachers
<div class="flex items-center justify-center mt4">
  <a href="http://caseywatts.com/"><img src="/headshot-casey.png" class="headshot"></a>
  <div class="ml5 measure-wide">
    <a href="http://caseywatts.com/" class="link"><div class="f3">Casey Watts!</div></a>
    <div class="f5 mt3">"Casey Watts!" currently works for Heroku. He works with Ember, React, Web Components, ES7+, Node, and Ruby. Casey has taught at a Yale University Web Development Bootcamp (Ruby on Rails + JS). He claims pair programming can triple the rate at which you learn. He has spoken and taught on several continents to audiences of up to 800 people. He never leaves home without bubbles.</div>
  </div>
</div>

<div class="flex items-center justify-center mt4">
  <a href="http://jonkeam.com/"><img src="/headshot-jon.png" class="headshot"></a>
  <div class="ml5 measure-wide">
    <a href="http://jonkeam.com/" class="link"><div class="f3">Jon Keam</div></a>
    <div class="f5">Jon Keam currently works at "It's Hospitality" where he builds tools for hospitality professionals. He works with React, Rails, React Native, WebSockets and Node. He has been a consultant at a company that prioritized both teaching in large groups and mentoring clients one-on-one. Jon believes teaching is best done by seeing the material through the students' eyes.</div>
  </div>
</div>

</div>
</div>

<div class="bg-purp-light pa5-ns tc flex items-center justify-center">
<div class="dib tl" markdown="1">

## Testimonials
<div class="flex items-center justify-center mt4">
  <img src="/headshot-steve.jpg" class="headshot">
  <div class="ml5 measure-wide">
    <div class="f3">Steve Chen</div>
    <div class="f5 mt3">"I never thought I'd make a desktop app with Javascript. I really liked the upbeat teaching style of Casey Watts - very entertaining and enthusiastic."</div>
  </div>
</div>

</div>
</div>


<div class="bg-purp pa5-ns tc">
<div class="measure-wide dib tl" markdown="1">
## Workshop Description
Electron provides a set of [cross-platform APIs](https://github.com/electron/electron-api-demos) you can use to interact with the desktop computer. You can use these to have an icon in the tray/menubar, to display notifications, register keyboard shortcuts, and much more. An Electron application has a node “server” running locally doing most of the work, and often additionally a browser process running locally to display things prettily.

No node experience required, but some basic JavaScript experience would be helpful. If you want to play with Node ahead of time anyway (or brush up on your Javascript), I'd recommend NodeSchool's two command-line courses: [Javascripting](https://github.com/workshopper/javascripting) and [LearnYouNode](https://github.com/workshopper/learnyounode). If you'd enjoy reading/skimming a book, I might recommend [Eloquent Javascript](http://eloquentjavascript.net/) (free to read online).

This class will walk students through creating a new JavaScript project from scratch. This class will also teach and reinforce [ES2017 fundamentals](https://github.com/lukehoban/es6features)
, potentially including:
  - arrow function
  - classes
  - enhanced object literal
  - template strings
  - destructuring
  - modules
  - let vs. const
  - default parameters
  - rest parameters
  - spread operator
  - promises
  - async/await

</div>
</div>




<div class="bg-purp-light pa5-ns tc">
<div class="measure-wide dib tl" markdown="1">
## Details
### Scenario / User Story
You work remotely. When pair programming or video chatting online, sometimes the connection gets bad.
You're never sure if it's your side or their side having issues.
Sometimes you smartly have a terminal open and have `ping google.com` running - then you can tell whether your connection is good!
You'd love it if:

1. You could tell at a glance (without an additional terminal window) whether your ping is currently good or bad
2. You could get a notification when your wifi goes out, or comes back


### Our Project
In this workshop, you will create from start to finish a tray icon that will display whether or not you are currently connected to the internet. A node process inside of the Electron app will ping google.com every second. We will then:

1. Use the tray api to change the app’s icon to reflect the current state
2. Display a notification when the internet appears to go up or down

You can see two example applications like this, here:

- https://github.com/groeneveld/am-i-connected
- https://github.com/caseywatts/electron-ping

And an unrelated application that I've written:

- https://github.com/caseywatts/heroku-ci-menubar

### Electron Resource Intensity
An electron menubar app uses RAM and CPU resources comparable to other menubar apps.

Casey's electron app `electron-ping` uses this amount of CPU and RAM to run:
- 0.9% CPU, 70.6 MB of RAM

Spot-checks of some other menubar apps running in the background:
- Dropbox 0.3% CPU, 165MB
- Screenhero 0.2% CPU, 124MB
- Google Drive 0.3% CPU, 151MB

</div>
</div>

<div>
<a href="https://ti.to/learn-shiny-things/learn-electron" class="link floaty">
  <div class="tc pa3 ba br4 b--purple bg-purp shadow-3">
    Sign Up
  </div>
</a>
</div>


<!-- Global Site Tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-107694077-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'UA-107694077-1', {'pagename': 'electron'});
</script>

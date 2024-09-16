# Retro-Tech-Challenges
A public repo that will be filled with technical programming challenges to (re)sharpen your skills

## Challenge 1

Write a single page (indext.html) web app that will be used as an Interval Timer.

### Technial Requirements:
- The web app can only be written in HTML, JavaScript & CSS
- The web app need to be able to run from opening it like a file or be hosted by a web server
- All content of the app needs to rside within the single index.html file
- No third party libraries can be used to generate, enhance or be needed to execute the web app

### Web App Requirements
#### The app has two modes
  - Running
  - Setup

#### The Running Mode
  - This is the first view a user will see
  - The screen will show the three data points outlined below
  - The running mode has three sets of data it displays
    - The Activity Timer that display & counts down the amount of Activity time remaining
    - The Rest Timer that displays & counts down the amount of Rest time remaining
      - This becomes activated when the Activity time reaches zero
    - The Rounds counter display how many rounds remain
  - The running mode has four controllers
    - Start
    - Pause
    - Stop/Reset
    - Setup
  - Start is actionable when a activity has not started or when an activity has been paused
  - Pause is actionable when a actiivty has been started
  - Stop/Reset is actionable all the time
    - Stop will end any running or paused activity and zero out all times & counters
    - Reset will reset all the timers & counters to the Setup values

#### The Setup Mode
  - This mode only displays when a user taps the Setup button from the Running Mode
  - The setup mode has three inputs
    - The Activity Time in seconds
    - The Reset Time in seconds
    - The Rounds amount as a whole number
  - The setup mode will have defaults
    - Activity is 40
    - Reset is 20
    - Rounds is 5
  - There are two  controllers
    - Reset
    - Lets Go
        - Taping this button saves the current set values and returns the user to the Running mode screen. 

### Web App Requirements (Bouns)
1. If you included externa graphics or assets, embed them into the index.html (full offline mode)
2. Allow the web app to be ran multiple times at once
3. Allow the web app to remember the last Setup that was used

### Submitting your work
1. Clone or Forks the repo
2. Do your amazing work
3. Open a PR so we can see what & how you've created the web app


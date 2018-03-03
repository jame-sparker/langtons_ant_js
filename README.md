# Langton's Ant JS
Javascript implementation of Langton's ant.

<img alt="Wikipedia demo" src="https://raw.githubusercontent.com/jame-sparker/langtons_ant_js/master/assets/la_wiki_sim.png"> 

## Description
This is a small one day project on Langton's ant implementation with javascript.
The major difference from other implementations online is that it runs on a webpage directly using text as a grid for ants.

## Requirements
- Chrome version later than 30 or
- Firefox version later than 29.
It should work on all major browsers.

## How to run
There are two main ways to run the code. One is to use javascript console and other is to use bookmarklet.

### Bookmarklet
1. Copy the code from `langtons_ant_min.js`. The file contains all code except for preceding `j`.
2. Open your favourite page on your browser and scroll to any part of the page.
3. In your address bar at the top, delete the current address, type in `j`, and paste the content of the file that you have just copied.
4. Press enter.

### Console
You can follow the same procedure from above and paste the code to javascript console on chrome which can opened with `F12` or copy 
the code from `langtons_ant.js`.
1. Copy the code from `langtons_ant.js`.
2. Open your favourite page on your browser and scroll to any part of the page.
3. Open javascript console with `F12`
4. Paste and run your in your console.

### Available Options (= default value)
- TILE_WIDTH (= 10)
- TILE_HEIGHT (= 10)
- NUMBER_OF_ANTS (= 3)
- MAX_STEPS (= 10,000)
- STEP_TIME (= 10) //ms

## Images
<img alt="Rosseta code demo" src="https://raw.githubusercontent.com/jame-sparker/langtons_ant_js/master/assets/la_ros_sim.png">

# Time App

## Current Release v1.0

---

This is a collection of timing apps that can be used to aid presenters. Designed to run full screen on a web browser and displayed on a downstage monitor. They have been optimized to run on displays that are 1920x1080.

- Once launched enter full screen mode by pressing the button, or pressing the "**F**" key.
- You can switch Apps by pressing the icons in the top left corner, or by pressing the "**D**", "**U**", or "**C**" keys.

---
**[Online Demo](https://paulbuchan.github.io/TimeApps/TimeApps.html)**
---

## App Instructions

---

### Countdown Timer 
Shortcut: **D**own

- Enter the time to countdown from at the bottom of the window.
- The warning time sets the time at which the screen will turn red.
- You must set the <b>Countdown Time</b> and the <b>Warning Time</b> before starting the timer. (Warning Time is optional)
- Press "Start" to begin, and "Stop" to pause/end.
- Once time ends, you'll need to "Reset" to start a new timer.
- Pressing "Warn" will toggle the background red.
- Once the countdown reaches the warning time the "Warn" button is no longer functional.
- The countdown is limited in display to double digit hours,
  although it will countdown from higher.

---

### Stopwatch (Timer)
Shortcut: **U**p

- Clicking "Start" will start the stopwatch.
- To pause/stop, press the "Stop" button.
- The "Reset" button resets the stopwatch to zero.
- "Toggle MS" will toggle the display of milliseconds on screen.
- The stopwatch will not display hours, it continues to count minutes.

---

### Clock
Shortcut: **C**lock

- Uses your system's clock to get the time.
- Use the buttons at the bottom of the page to toggle between 12hr/24hr time, displaying the AM/PM, and if seconds are displayed.

---

## Duplicate Screen Instructions

---

### Windows

1. Connect your computer to a second display or projector.
2. Right-click on your desktop and select "Display settings."
3. Under "Multiple displays," select "Duplicate these displays."
   <b>Your computer screen should now be duplicated on the second display.</b>

### Mac

1. Connect your computer to a second display or projector.
2. Click on the Apple menu and select "System Preferences."
3. Click on "Displays" and then select the "Arrangement" tab.
4. Check the box next to "Mirror Displays."
   <b>Your computer screen should now be duplicated on the second display.</b>

---

---

These are written in HTML, CSS, and JavaScript so that they can easily be run without any additional tools/software installed. You can also use them on or off-line. The only file needed is <i>TimeApps.html</i>

---

---

## Change Log

> #### v1.0 - 2023.03.26
>
> - Initial Public Release
> - Minor bug fixes & improvements

> #### v0.7 - 2023.03.25
>
> - Added Shortcut Keys to switch Apps
> - Fixed spacing
> - Minor bug fixes & improvements

> #### v0.6 - 2023.03.24
>
> - Fixed Reset bug - Countdown
> - Added Leading Zero in 24hr time - Clock
> - Minor bug fixes

> #### v0.5 - 2023.03.23
>
> - Major Update --> Single page experience
> - All existing features in place
> - Countdown: Added persistent colon in front of seconds

> #### v0.4 - 2023.03.22
>
> - Countdown - <b>Warn</b> button now toggles warning state
> - Pressing <b>F</b> key toggles full screen mode
> - Fixed sizing issue on Stopwatch
> - Defaulted Clock App to 12hr view with AM/PM enabled
> - Added App icons at top of page for App switching
> - Corrected grammar and spelling on Index page

> #### v0.3 - 2023.03.19
>
> - Updated all Apps to include Full screen Button
> - Index page updated to reflect Full screen changes
> - Footer added to Index
> - Resized Timer App display to fit screen better
> - Code cleanup
> - Updated Readme
> - Initial Release Build

> #### v0.2 - 2023.03.18
>
> - Unified button design and layout across apps
> - Bug fixes

> #### v0.1 - 2023.03.18
>
> - Initial GitHub Commit

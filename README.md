# sleep-control.js  

#### Prevent devices from dimming, locking or turning off the screen when the application needs to keep running  

Mobile devices respect you when you watch a video on a page or app and wait until the video ends before switching to sleep mode.  
But they don't respect you the same way when you watch an image slideshow and they often dim the screen before the slideshow is over, which is annoying.

__sleep-control.js__ tries to solve this problem by playing a tiny little invisible video and an inaudible audio to extend the sleep timeout so that your users can watch the contents of your app without the UX being cut in the middle.

### [You can try it here](https://topraksoyearthmantsuchimoto.github.io/sleep-control.js/)  if you are using a mobile device
---

##### [Download sleep-control.js | Right-click here and Save as…](https://raw.githubusercontent.com/TopraksoyEarthmanTsuchimoto/sleep-control.js/main/sleep-control.js "Right-click Save As…")
***

To adjust the *stay-awake* time you can use the `tryToStayAwakeAtLeastThisLong(seconds)` function before `load` event fires on window.  
The default is 99 seconds.

###### sleep-control.js was created during the development of [speakworldlanguages.app](https://speakworldlanguages.github.io)

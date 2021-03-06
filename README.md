# countdown-timer

A basic Jekyll template designed to create a customizable timer on GitHub Pages, based on my earlier [lightning-time](https://github.com/evanwill/lightning-time) site.
Generates a super simple web page based timer with a buzzer, [demo](https://evanwill.github.io/countdown-timer/).

Only works in modern browsers. 

I use it on Firefox, full screen mode, on a touch screen laptop, folded in stand mode, making a lovely timer for an event.

## Customize

Fork/import or otherwise copy the repo. 

Edit the `_config.yml` file with your info. 
All the timer customization options are in the `_config.yml`.
Add any new backgrounds to `images` folder and new mp3 sounds to the `sounds` folder.

Edit the about if desired.

Active GitHub Pages in your repository settings. 

## Use

Click "Ready" to start; at the end click "0:00" to reset. 

Default is five minutes with a caution color at two minutes and warning color at one minute. 

To customize the time, add "#" with time,warning (for example, one minute with warning at 30 sec: lightning-time/index.html#60,30).

Inspired by and based on <a href="https://github.com/apg/timer" target="_blank">apg/timer</a> and <a href="https://github.com/mithro/lightningtimer" target="_blank">mithro/lightningtimer</a> projects.

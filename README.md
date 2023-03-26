# Komodoro 🍅⏰🔒
A "pomodoro timer" for making pauses at your PC. Locks the screen every half hour for 5 minutes, so that you make a break.

- After login your screen will be locked in 30min for 5min, like "pomodoro" but in KDE-wide
- If you want to pause the timer, execute the dedicated Appstarter named "Pause Komodoro" It will pause the timer and resume after a given amount of minutes
- If you enter `komodoro-remove` in the Terminal, it gets wiped from your system.

Install
```
curl -s https://github.com/trytomakeyouprivate/Komodoro/raw/main/komodoro-install | bash -s
```



## Todo

- display these messages when unlocked

```
notify-send -a "Komodoro" "Working time!" "30 minutes left"
sleep 600
notify-send -a "Komodoro" "Working time!" "20 minutes left"
sleep 600
notify-send -a "Komodoro" "Working time!" "10 minutes left"
sleep 300
notify-send -a "Komodoro" "Working time!" "5 minutes left"
sleep 300
```

- check if timer continues even with locked screen, avoid that
- test!

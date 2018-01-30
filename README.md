# Pomoshoro

Simple pomodoro script to boost focus and productivity

## Features

- Notification using YAD
- Display real-time countdown
- Use compliment words to motivate user
- Display how many times you have worked
- Infinite pomodoro session

## Getting Started

### Prerequisites

- Yad
- aplay

You can get them from your favourite distribution packages

```
 apt install alsa-utils  yad
```

### Installing

You can put `pomoshoro` in your home directory or `/usr/local/bin`

``` bash
git clone https://github.com/azzamsa/pomoshoro ~/pomoshoro
cd ~/pomoshoro
chmod +x pomoshoro
./pomoshoro
```

The nice way is to auto-start `pomoshoro` with your window-manager or desktop-environment

**Don't forget to** create `~/sounds` directory and put any sounds you want, then change the song name in [pomoshoro script](https://github.com/azzamsa/pomoshoro/blob/6d9860d3f98c620e591ad6b559f6e8268f660136/pomoshoro#L16) according to your sound name.

## Authors

- Azzam S.A

## License

This project is licensed under the GPLv3 License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- Great thanks for Reza Azzubair W who has told me about pomodoro technique in 2016.
- Inspired by [Waldir Leoncio](https://superuser.com/users/120246/waldir-leoncio) in [Pomodoro timer for linux](https://superuser.com/questions/224265/pomodoro-timer-for-linux#669811)
- [Timer function](https://superuser.com/questions/611538/is-there-a-way-to-display-a-countdown-or-stopwatch-timer-in-a-terminal#611582) by [Terdon](https://superuser.com/users/151431/terdon)

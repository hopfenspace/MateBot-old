# MateBot

Sells Mate (and other drinks). So you dont have to put a coin in the jar every time.

Written in [PointerScript](https://github.com/M4GNV5/PointerScript) (considered Haskell first, but too much State)
It uses the Telegram API from [PtrsStuff](https://github.com/M4GNV5/PtrsStuff). After installing PointerScript and cloning PtrsStuff, do something like the following to make it work:
```sh
ln -s ../PtrsStuff/libs libs
ptrs mate.ptrs
```

You need to obtain a Telegram bot token and set it in mate.ptrs.

## Features

- [X] Buy a drink
- [X] Show your balance
- [ ] Pay for the drinks (Using the [Telegram Payment API?](https://telegram.org/blog/payments))
- [ ] Track Drink storage (and alert when running low)

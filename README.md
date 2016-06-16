homebridge-custom-garagedoor
============================

Custom GarageDoor plugin for [HomeBridge](https://github.com/nfarina/homebridge)

## Configuration

Configuration sample:

 ```
    "accessories": [
        {
            "accessory": "CustomGarageDoor",
            "name": "Garage Door",
            "url": "https://someurl.com",
            "doorOpensInSeconds": 14
        }
    ],
```

Fields: 

* "name": Can be anything (required)
* "url": Path to [the server](https://github.com/jordanbyron/alarm_keypad/tree/garage_door)
* "doorOpensInSeconds": Number of seconds it takes your garage door to open or close (err on the side of being longer than it actually takes)

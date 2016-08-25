Pikaday - With Time Picker
========

### Key Config Changes

```javascript
showTime: true
showSeconds: false
use24hour: false
incrementHourBy: 1
incrementMinuteBy: 1
incrementSecondBy: 1
autoClose: true
timeLabel: null // optional string added to left of time select
```

### Time support added to [dbushell/Pikaday][david Pika]

This fork allows the user to specify the time along with their date. Done so by adding a couple select inputs to manipulate the date Pikaday is generating.
* Used to set time aspects of date.
* Will not change the currently selected date.
* If no date is selected, will select today. Any of the arguments may be null, and will not affect the date.

### Also includes a whole week selector for Pickaday taken from [leizhao4/Pikaday][leizhao4 Pika]

use `pickWholeWeek` to select a whole week instead of a day (default `false`)

## Authors

* Owen Mead-Robins [http://www.owenmead.com/][owenmead]

[david Pika]:   https://github.com/dbushell/Pikaday                              "Pikaday"
[owenmead]:     http://owenmead.com/                                             "owenmead.com"

Friendly timezones
---

A friendly list of timezones that gives you:
- a timezone offset,
- a display name
- the timezone name based on the IANA timezones database.

### Installing

```shell
npm install --save github:thiagodelgado111/friendly-timezones.git
```

### How do I use it?

```js
import timezones from 'friendly-timezones`;

console.log(timezones);
//  {
//    zones: [{
//      id: 'Asia/Kuala_Lumpur', displayName: '(UTC+08:00) Kuala Lumpur, Singapore', utcOffset: 8
//    }, {
//      (...)
//    }, {
//      id: 'Asia/Pyongyang', displayName: '(UTC+08:30) Pyongyang', utcOffset: 8.5
//    }]
//  }
```

It was based on `Slack`'s timezones arrangement, (vahnag/react-timezones)[https://github.com/vahnag/react-timezone] and (dmfilipenko/timezones.json)[https://github.com/dmfilipenko/timezones.json]

### Contributing
Please feel free to file an issue or send your PR :)

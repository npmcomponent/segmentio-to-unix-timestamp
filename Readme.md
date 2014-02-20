*This repository is a mirror of the [component](http://component.io) module [segmentio/to-unix-timestamp](http://github.com/segmentio/to-unix-timestamp). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/segmentio-to-unix-timestamp`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# to-unix-timestamp

  Convert a date to a Unix timestamp.

## Installation

    $ component install segmentio/to-unix-timestamp

## Example

```js
var unix = require('to-unix-timestamp');

unix(new Date());
// 1380249249
```

## API

### toUnixTimestamp(date)
  
  Returns the Unix timestamp of a `date`.

## License

  MIT

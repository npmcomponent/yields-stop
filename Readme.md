*This repository is a mirror of the [component](http://component.io) module [yields/stop](http://github.com/yields/stop). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-stop`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# stop

  Cross-browser `.stopPropagation`.

## Installation

    $ component install yields/stop

## Example

```js
anchor.onclick = require('stop');
```

## API

### stop(e)

  Stop the given `e`, if the argument is omitted,
  the method will fallback to `window.event`.   

## License

  MIT

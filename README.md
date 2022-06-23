# megamind-logger

This very useful package allows you to paste our famous megamind character from 'no bitches?' meme straight to your console.

## Features:
- Log your errors with STYLE
- pretty much that's all (more coming soon)

## Setup:

First of all, you must download this package using npm.

```npm i megamind-logger```

Next, install all required depencencies (should work without it but whatever):

```npm i chalk@4.1.2```

You're done! Now just export this module into your code. Here's an example.
```js
const { megamindLog } = require('megamind-logger');

// your code

if(!connection) {
    megamindLog('No connection?')
}

//your code
```

### That's all, I think. If you want to contribute PR's are all yours!

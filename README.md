# bland

Basic default console logger using console.blahs (as console.debug doesn't exist in node).

```javascript

module.exports =
  { info: console.info
  , log: console.log
  , error: console.error
  , warn: console.warn
  , debug: console.log
  , trace: console.trace
  }

var logger = require('bland')

logger.info('boring bland logs')

```

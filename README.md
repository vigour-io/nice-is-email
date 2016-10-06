# nice-is-email

<!-- VDOC.badges travis; standard; npm; coveralls -->
<!-- DON'T EDIT THIS SECTION (including comments), INSTEAD RE-RUN `vdoc` TO UPDATE -->
[![Build Status](https://travis-ci.org/vigour-io/nice-is-email.svg?branch=master)](https://travis-ci.org/vigour-io/nice-is-email)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)
[![npm version](https://badge.fury.io/js/nice-is-email.svg)](https://badge.fury.io/js/nice-is-email)
[![Coverage Status](https://coveralls.io/repos/github/vigour-io/nice-is-email/badge.svg?branch=master)](https://coveralls.io/github/vigour-io/nice-is-email?branch=master)

<!-- VDOC END -->

<!-- VDOC.jsdoc isEmail -->
<!-- DON'T EDIT THIS SECTION (including comments), INSTEAD RE-RUN `vdoc` TO UPDATE -->
#### var valid = isEmail(val)

Checks whether provided parameter looks like a valid e-mail address
- **val** (*string*) - the string to check
- **returns** (*boolean*) valid - `true` if `val` is a valid e-mail address, `false` otherwise

<!-- VDOC END -->

```javascript
var isEmail = require('nice-is-email')
isEmail('foo@bar.com') // true
isEmail('@bar') // false
```
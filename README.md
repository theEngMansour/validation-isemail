<img src="https://i.ibb.co/bKfZ17J/Untitled-1-01.png" alt="Untitled-1-01">
# validation-isemail

Node email address validation library
Lead Maintainer: [Mansour Ahmed][theEngMansour]

Install
=======

```sh
$ npm install validation-isemail
```
### Examples

```js
$ node
> import { isEmailValid } from "validation-isemail";

> isEmailValid('test@iana.org');
true
> isEmailValid('testiana.123');
false
```
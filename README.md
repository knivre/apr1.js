# apr1.js
A JavaScript implementation of the APR1 hash.

Requires md5.js from [Paul Johnston's jshash](http://pajhome.org.uk/crypt/md5/)

Basic usage:

```javascript
var password = 'qLs9nAXjyHQRbfDKsNfnhqJJQ2hVmv';
var hash = apr1_hash(password); // e.g. $apr1$ZNMOSPte$M5c02r7G1ZvLi/47fuRLa1

apr1_is_hash(password); // false
apr1_is_hash(apr1_hash); // true
```

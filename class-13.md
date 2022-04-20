
### Reading 13 Local Storage
- Web doc http://diveinto.html5doctor.com/storage.html

---
### Diving In
1. What we want for storage is 
  - alot of storage space
  - on the client
  - that persists beyond a page refresh
  - isnt transmitted to the server

2. userData allows web pages to store up to 64kb of data per domain in XML based structure

### HTML 5
1. Refered to as locat storage or DOM storage by certian browsers
2. Its a way for web pages to store named key/value pairs locally within the clients web browsers
3. But unlike the regular cookies this data is never trasmitted to the remote web server
4. It is implemented natively in web browsers so its available when third party plugins are not
5. In JS code youll access HTML 5 storage though localstorage objects on the global windown objects

### Using html5
1. Based on named key/value pairs
2. Store data on a named key than you can also retrieve that data with the same key, the named key is a string.
3. If you are storing anything other than a string you will need to use a function

### Limitations in current browsers
1. 5 megabytes is the amount of storage space each origin recieves by default
2. Storing lots of data like integers or flots the data storage amount adds up
3. Over 5 megabytes you will get an error

### Beyond named key-value pairs
1. Due to the limitation of 5 megabytes other options have arrived
2. SQL,SQL database provies a thin wrapper around SQL database allowing you to do things from JS
3. The Indexed Database API, exposes an object store, still in the works

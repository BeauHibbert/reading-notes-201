# The past present and future of local storage for web applications
Notes from diveinto.html5doctor.com/storage.html
## Cookies were invented in the web’s early history, and can be used for persistent local storage of small amounts of data. But they have three potentially deal breaking downsides
- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet(unless your entire web app is served over SSL)
- Cookies are limited to about 4 KB of data - enough to slow down your application but not enough to be terribly useful
## What we really want is
- A lot of storage space
- On the client
- That persists beyond a page refresh
- isn’t transmitted to the server
## HTML5 storage is a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the website, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugin are not.
## HTML5 storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JS, including strings, booleans, integers, or floats. However the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JS datatype.
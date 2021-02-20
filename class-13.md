# Class 13 Reading Summary

## Storage

- Local storage is one of the areas where native client apps holds an advantage over web apps.
- For native apps, the operating system typically provide an abstration layer for storing and retrieving application-specific data like preferences or runtime state; These values may be stored in the registry, INI files, XML files, or some other place according to platform convention.
- Cookies were invented early in the web's history which can be used for perfsistent local storage of small amounts of data but they have three downsides:
1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
1. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
1. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful
## HTML5 Storage
- HTML5 Storage is also named Web Storage, Local Storage, DOM Storage
- HTML5 Storage is a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server
- HTML5 is supported by IE, Firefox, Safari, Chrome, Opera, Iphone, Android
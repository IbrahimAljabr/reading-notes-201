## Read 13 :

# Local Storage :

* Persistent local storage is one of the areas where native client applications have held an advantage over web applications

* Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

* Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over .

* Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL) .

* Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful .

# What we really want is :

* a lot of storage space .

* on the client .

* that persists beyond a page refresh .

* and isn’t transmitted to the server .

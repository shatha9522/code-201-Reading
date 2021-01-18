## What is HTML Web Storage?
With web storage, web applications can store data locally within the user's browser.

Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server.

Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.

## HTML Web Storage Objects
HTML web storage provides two objects for storing data on the client:

window.localStorage - stores data with no expiration date
window.sessionStorage - stores data for one session (data is lost when the browser tab is closed)

## The localStorage Object
The localStorage object stores the data with no expiration date. The data will not be deleted when the browser is closed, and will be available the next day, week, or year.
 
 ## In the past
 Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful
What we really want is

a lot of storage space
on the client
that persists beyond a page refresh
and isn’t transmitted to the server
Before HTML5, all attempts to achieve this were ultimately unsatisfactory in different ways.
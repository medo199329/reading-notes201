# HTML5


HTML5 is a markup language used for structuring and presenting content on the World Wide Web. It is the fifth and last[3] major HTML version that is a World Wide Web Consortium (W3C) recommendation. The current specification is known as the HTML Living Standard. It is maintained by a consortium of the major browser vendors (Apple, Google, Mozilla, and Microsoft), the Web Hypertext Application Technology Working Group (WHATWG)

**Local Storage
**

HTML5 has proven a solution to many attempts to solve problems that occurred a long time ago Provide a standard API, implementation locally and consistently in multiple browsers, without having to rely on third-party plug-ins

the data is stored as a string and based on named key/value pairs then you can retrieve that data with the same key

With web storage, web applications can store data locally within the user's browser.Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server. Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.

With web storage, web applications can store data locally within the user's browser.

Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

for more information:
[W3 schools](https://www.w3schools.com/html/html5_webstorage.asp).

HTML Web Storage Objects
HTML web storage provides two objects for storing data on the client:

window.localStorage - stores data with no expiration date
window.sessionStorage - stores data for one session (data is lost when the browser tab is closed).

``if (typeof(Storage) !== "undefined") {
  // Code for localStorage/sessionStorage.
} else {
  // Sorry! No Web Storage support..
}``
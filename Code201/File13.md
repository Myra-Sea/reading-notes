# 🐳 Introduction to Persistence with Local Storage 🐳


## 📝 Assigned Homework Questions:

❓ Why would a developer use local storage for a web application?

A local copy allows for offline access, potentially greater security, a reduced load on the server, and it allows for data persistence (ie. access to the most up-to-date version that won't revert to its original state when the app is closed).

❓ What information should not be stored in local storage?

Sensitive or security-related information such as session tokens, user credentials, or payment details (such as credit card numbers).

❓ Local storage can store what type of data? How would you convert it to that type before storing?

It's designed to store data as strings. It can be converted using JavaScript's `toString()` method. 

<br>

## 📚 Links to the Assigned Reading:

[Local Storage and How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

[“The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html)

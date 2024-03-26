# Local Storage & How to use it on Websites

### 1) Why would a developer use local storage for a web application?
The main problem with HTTP as the main transport layer of the Web is that it is stateless. This means that when you use an application and then close it, its state will be reset the next time you open it. If you close an application on your desktop and re-open it, its most recent state is restored. This is why, as a developer, you need to store the state of your interface somewhere. This is where Local Storage can be useful! <br> The classic way to do this is by using a cookie. A cookie is a text file hosted on the user’s computer and connected to the domain that your website runs on. You can store information in them, read them out and delete them.
### 2) What information should not be stored in local storage?
Local storage should be used for storing non-sensitive, non-critical data that enhances the user experience of your web application. For sensitive or critical information, consider alternative storage mechanisms that provide stronger security and privacy guarantees. Sensitive information would include things like: user passwords, personally identifiable data, private business data, etc.

### 3) Local storage can store what type of data? How would you convert it to that type before storing?
Local Storage can only store string data. So in order to store data, it will need to be converted to string data. By converting data to strings before storing it in local storage, you ensure that the data can be retrieved and used accurately when retrieved from local storage. When retrieving data from local storage, you may need to convert it back to its original data type using methods like parseInt(), parseFloat(), JSON.parse(), etc., depending on the data type.

## Resources
- [Local Storage & How to Use it](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)<br>
- [The Past, Present & Future of Local Storage for Web Applications](https://diveinto.html5doctor.com/storage.html)<br>

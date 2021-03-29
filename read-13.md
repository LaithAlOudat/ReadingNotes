### Local storage:

##### The Storage type provides you with the methods for storing and managing data in the web browsers.
##### The localStorage is an instance of the Storage type that allows you to store persistent data in the web browsers.
##### The localStorage can store only strings. To store objects, you convert them to strings using the JSON.stringify() method. And you convert the strings into objects when you retrieve them from the localStorage using the JSON.parse() method.
##### The Storage type is designed to store name-value pairs. The Storage type is an Object with the following additional methods:

###### setItem(name, value) – set the value for a name
###### removeItem(name) – remove the name-value pair identified by name.
###### getItem(name) – get the value for a given name.
###### key(index) – get the name of the value in the given numeric position.
###### clear() – remove all values.
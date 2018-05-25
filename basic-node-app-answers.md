>What is a Node module?

A node module is just a set of functions that can be included in an application. They are essentially JS libraries.

>What is the main difference between exports and module.exports?

`module.exports` is the object returned from `require()` and is empty by default, meaning methods and variables can be added to it directly. `exports` is simply a reference to `module.exports`

>Why is using exports recommended?

Exports is recommended except when your module is a specific object type. `Exports` is a reference to `module.exports` and cannot reassign the object `module.exports`

# ReactNativeBlog
React Native Blog Post App as a part of the Udemy React Native course

A interesting React Native Blog Post app that achieve data persistense through a json/ngrok backend API and making calls to the locally hosted API to store the data sent from the client.
It also shows how to make a context provider that can encapsulate the rest of the project to provide needed context instead of having to inherit it directly from parents.

So as an example instead of doing:
Index -> IndexChild -> EditIndexChild
I can do:
ContextProvider -> EditIndexChild

This makes it easier to keep track of what data I pass through each screen and also have a centerpoint where I can store the defined method that I need to use and make it easier to modify them.

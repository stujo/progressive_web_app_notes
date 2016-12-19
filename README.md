# Progressive Web Apps

* [Angular 2 and Progressive Web Apps - Google I/O 2016](https://www.youtube.com/watch?v=vAb-2d1vcg8)

# Beyond SPA Apps

* Pushing a lot of code to the client isn't great
* But we want an 'App Like' experience
* Native like experience

# Application Loading

* Application Shell - Static UI in the index.html file
* Declarative

# Angular 2 - Features

* Angular Pre-Render 

  - Part of the build process
  - or at runtime on for node.js and .NET
  - ``expressEngine`` from ``@angular/universal`` processes ``.html`` files before serving

* Break Application Code into Modules

  - Modules only loaded by the router as needed

* Service Worker - little HTTP server that runs in the browser 
  - but not widely supported http://caniuse.com/#feat=serviceworkers

* 

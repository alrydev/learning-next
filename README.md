## Routing /app


1. Add:<br/> experimental:{
 appDir: true
} <br/>
inside  next.config.js file

2. Create app folder to store all the files, it works the same way as pages folder previosly. Also page.tsx file works the same way as index.tsx file 


In this example, the page.tsx inside the dashboard folder, and page.tsx inside the app folder are turned into routes that can be accessed at `/dashboard`, `/` respectively.


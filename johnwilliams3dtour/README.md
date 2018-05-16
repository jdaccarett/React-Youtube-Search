# 3D room tour with theme music

Install dependencies and start your engines! This ships with a simple express.js server so we can run three.js properly without cross-origin issues.

```bash
$ npm install
$ npm run start
```

Open http://localhost:3000 to see project.

The code might look a little funky because most of the code is inside one EventListener(start tour button). I did this to bypass the chrome updated policy on creating audioContext only on user gesture else the video is muted on most chrome browsers.

Note: you can also run $ nodemon index.js
this will avoid you from having to reload the page everytime.

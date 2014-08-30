# Offline news - server rendered with *AppCache* [ ![Codeship Status for matthew-andrews/offline-news-server-rendered](https://codeship.io/projects/8397dcc0-129c-0132-6986-7e4352749945/status)](https://codeship.io/projects/33244)

https://offline-news-server-rendered.herokuapp.com

### Prerequisites

UNIX-like computer running node (would happily accept pull requests to fix it for Windows but I don't have the means to test that here).

Install a copy of **[offline-news-api](https://github.com/matthew-andrews/offline-news-api)** and run locally (follow instructions on that repository).

### Install and run

```
git clone git@github.com:matthew-andrews/offline-news-server-rendered.git
npm install
node index.js
```

### Overview

- [Client side application logic](./blob/master/public/application.js)
- [Client side AppCache hacks](./blob/master/public/appcache.js
- [Server (express) logic](./blob/master/index.js)

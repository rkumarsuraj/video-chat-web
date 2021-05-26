# Talk

## A free group video call app with screen sharing.

It is built using WebRTC, so all your video, audio & text chat is peer-to-peer. Group video call is achieved using WebRTC mesh. So the quality of the call is inversely proportional to the number of people on the call. The sweet number is somewhere around 6 to 8 people in an average high-speed connection.

### Prerequisites:

- Node.js 8.x or above
- NPM

### How to Build this app locally

Clone the repo locally, or extract the contents of the source code.

`cd talk` and then install dependencies

```
npm install
```

Run the app

```
npm start
```

Open the following url in the browser

```
http://localhost:3000
```

### Docker compose

[NGINX proxy](https://hub.docker.com/r/jwilder/nginx-proxy) container with [its companion](https://github.com/nginx-proxy/docker-letsencrypt-nginx-proxy-companion) to proxy the access to the app and generate a SSL certificate with [Let's Encrypt](https://letsencrypt.org/).


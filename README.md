An introductory project on Go. My first one. It simply exposes an endpoint '/ping' that responds with 'pong' :)

Inspired from :
https://www.youtube.com/watch?v=C5y-14YFs_8

## RUN

- `docker build . -t go-first-app:latest`
- `docker run -e PORT=9000 -p 9000:9000 go-first-app:latest`

![2023-11-03_21-30](https://github.com/cvairlis/go-simple-ping/assets/10025897/16c2bb07-4dab-420a-a16c-42f0063987f2)

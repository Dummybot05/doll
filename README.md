```bash
docker build -t xrdp .


docker run -d -p 3389:3390 -v xrdp-root-home:/root --name xrdp-root-wine-audio xrdp

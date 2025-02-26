GIT_COMMIT=$(git rev-parse --short HEAD)
docker build -t ahgia/proxy-doih:$GIT_COMMIT -f ./Dockerfile.doih .
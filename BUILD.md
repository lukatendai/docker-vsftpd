docker login -u lukatendai
docker build -t ftp .
docker tag ftp lukatendai/ftp:TAGNAME
docker push lukatendai/ftp:TAGNAME

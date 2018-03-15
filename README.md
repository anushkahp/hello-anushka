# hello-anushka
Commands:

docker build -t finalhello .
docker run -p 4000:80 -e NAME="Anushka" finalhello

Using the -e NAME="Anushka" the value of the NAME variable is supplied at runtime

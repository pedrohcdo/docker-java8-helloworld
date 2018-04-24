# compile class
javac helloworld.java

# build image
docker build -t java8-helloworld .

# run image
docker run -it --rm --name my-running-app java8-helloworld

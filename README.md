# docker-swift
Docker Container for the Apple's Swift programming language https://swift.org

### An Ubuntu 15.10 Docker image for [Swift](https://swift.org).

#### You can find the Docker Hub repo here: [https://hub.docker.com/r/livetribe/swift](https://hub.docker.com/r/livetribe/swift)


### Docker Instructions

##### Pull the Docker Image From Docker Hub:

```bash
docker pull livetribe/swift
```

##### Create a Container from the Image and Attach It:

```bash
docker run --privileged -i -t --name swiftfun livetribe/swift:latest /bin/bash
```

##### To Start and Attach Your Image Later:

Start your image with name `swiftfun`

```bash
docker start swiftfun
```

and then attach it

```bash
docker attach swiftfun
```


## Contributions

Contributions via pull requests are welcome and encouraged :)

## License

docker-swift is licensed under the [MIT License.](LICENSE.md)
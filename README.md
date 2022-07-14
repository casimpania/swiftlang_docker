# Get, build and start
```
~$ git clone https://github.com/casimpania/swiftlang_docker.git
~$ cd swiftlang_docker
~$ cp .env-sample .env
~$ docker-compose build
~$ docker-compose up -d
```

# Shell-in
```
~$ docker-compose exec swift /bin/bash
```

# Hello Swift
```
~$ swift --version
Swift version 5.6.2 (swift-5.6.2-RELEASE)
```

# Optional
You can use docktie if you aren't too familiar with docker in the meantime - https://github.com/docktie/docktie

# Credits
Docker container is about 98% from https://github.com/apple/swift-docker/tree/main/5.6/centos/7/slim

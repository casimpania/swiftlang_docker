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

# Swift Learning Resources
* https://docs.swift.org/swift-book/index.html
* https://www.programiz.com/swift-programming

# Optional
You can use docktie if you aren't too familiar with docker in the meantime - https://github.com/docktie/docktie

# Credits
Dockerfile is roughly 78% from https://github.com/apple/swift-docker/tree/main/5.6/centos/7/slim.
22% or 16/73 lines are from my customizations.

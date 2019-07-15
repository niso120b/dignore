# dignore - dockerignore generator

**dignore** cli tool in golang to auto generate .dockerignore file by your Dockerfile and your context.
using cobra to implement cli tool

# Build

* Mac
```bash
CGO_ENABLED=0 GOOS=darwin GOARCH=amd64 go build -o bin/dignore-mac
```

* Linux
```bash
CGO_ENABLED=0 GOOS=linux GOARCH=amd64 go build -o bin/dignore-linux
```

# Developer
Nissim Bitan - niso120b@gmail.com, nissim.bitan@aquasec.com

# rpi-python
Docker Image packaging for Python, used for Raspberry Pi

### build the Docker Image
```bash
make build
```

### run the Docker Image and get version of installed Python
```bash
make version
```

### push Docker Image to Docker Hub
* First, use a `docker login` with username, password and email address
* Second, push Docker Image to the official Docker Hub
```bash
make push
```

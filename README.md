# Malicious Test Docker Image 

This docker image is intended to emulate malicious behavior to test EDR/Anti Virus solutions on Docker/Kubernetes Hosts/Clusters.

## How To Run
```
git clone https://github.com/medoix/malicious-docker && cd malicious-docker
docker build -t malicious-docker:latest .
docker run malicious-docker:latest
```

## What Tests are Running?

### Anti Virus
[EICAR Malware Sample](https://www.wicar.org/test-malware.html)

### Network Endpoint Protection
[Flightsim Malicious Network Sample](https://github.com/alphasoc/flightsim)
# malicious-test-docker 

Malicious Docker Image - This docker image is intended will emulate malicious behavior to test EDR/Anti Virus solutions on Docker/Kubernetes Hosts/Clusters.

## How To Run
```
git clone https://gitlab.com/medoix/malicious-test-docker && cd malicious-test-docker
docker build -t malicious-test-docker:latest . 
docker run malicious-test-docker:latest
```

## What Tests are Running?

# Anti Virus
[EICAR Malware Sample](https://www.wicar.org/test-malware.html)

# Network Endpoint Protection
[Flightsim Malicious Network Sample](https://github.com/alphasoc/flightsim)
# Docker_practical

#######################These practicals are done on self made projects######################

-->docker basics

-->multistage docker

-->docker networking

-->docker containers and bind mounts



Real challenges of haivng docker:

1.docker daemon- single point of failure..if docker daemon down whole process fails.
alternative: podman->performs same instructions as docker with no single point of failure

2.docker daemon runs as root: so vulnerable ,security threat

3.resource constraints: if too many resources running together , it causes slow performance.

Security measures:

1.use distroless images with not too many packages and multistage build.

2.ensure network is properly configured. if needed use custom bridge net.

3.scan container images using utilities Sync.

# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-gnbsim_1.3_amd64.rock docker-daemon:sdcore-gnbsim:1.3
docker run sdcore-gnbsim:1.3
```

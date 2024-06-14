# Contributing

## Build and deploy

```bash
sudo snap install rockcraft --classic --edge
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-gnbsim_1.4.3_amd64.rock docker-daemon:sdcore-gnbsim:1.4.3
docker run sdcore-gnbsim:1.4.3
```

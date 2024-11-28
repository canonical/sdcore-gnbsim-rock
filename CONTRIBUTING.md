# Contributing

## Build and deploy

```bash
sudo snap install rockcraft --classic --edge
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:sdcore-gnbsim_1.5.0_amd64.rock docker-daemon:sdcore-gnbsim:1.5.0
docker run sdcore-gnbsim:1.5.0
```

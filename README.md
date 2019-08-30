# MAIND

Molecule + Ansible in Docker!

Use this image to run molecule tests and/or run Ansible from docker images. No need to manage Python module versions or worry about virtual environments.

To use this just type:

```
docker run -ti --rm -v <YOUR_ANSIBLE_DIR>:/ansible -v /var/run/docker.sock:/var/run/docker.sock --name MAIND --hostname MAIND marcelom/maind
```

# vagrant-ubuntu-docker

Since Docker for Mac doesn't always works well, so I created this
Vagrantfile which describes a VM with Docker installed.

To use this VM:

```
git clone https://github.com/wangkuiyi/vagrant-ubuntu-docker
cd vagrant-ubuntu-docker
vagrant up
vagrant ssh
```

Then we can run Docker commands like

```
docker run hello-world
```

Please be aware that this Vagrantfile mounts `~/work` on the host into
`/work` in the VM.

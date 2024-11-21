# awx-standalone-setup
Minimal standalone setup to deploy Ansible AWX for production.

## Development

For test purposes, use `limactl` to spin up a `debian12` virtual machine with the name `kube`. The default inventory is configured to use this virtual machine.

```shell
limactl create kube
```

## Install

See [INSTALL.md](INSTALL.md).

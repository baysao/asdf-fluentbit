# asdf-fluentbit

[Fluentbit](https://fluentbit.io/) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

## Install
Process will need cmake, flex, bison. Please install it before add plugin.
This setup base on [fluent-bit-packaging](https://github.com/fluent/fluent-bit-packaging/blob/master/distros/ubuntu/16.04/Dockerfile)

```
asdf plugin-add fluentbit https://github.com/baysao/asdf-fluentbit.git
```

## Use

After install, binary is td-agent-bit

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of Fluentbit.

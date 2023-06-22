# Contributing

Build the snap:

```console
snapcraft pack --verbose
```

This command will have created a snap artifact in your local directory, in this case `pysim_7e55569f3a_amd64.snap`. 

Install the snap locally:

```console
sudo snap install ./pysim_7e55569f3a_amd64.snap --dangerous
```

Run `pysim` commands:

```console
pysim.shell --device=/dev/ttyUSB0
```

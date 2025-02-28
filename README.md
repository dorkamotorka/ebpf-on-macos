# eBPF on MacOS - Actually on Lima

If you've never heard of [Lima](https://lima-vm.io/), it allows one to spawn virtual machines on MacOS.

I find it pretty convenient, so I decided to show you how to run eBPF code with it. Or even better, give you the fully fledged eBPF development environment.

For this reason, there's a `default.yaml` file that you can utilize to create a VM - preconfigured to work with your eBPF programs, just by running:

```
limactl create --name=default default.yaml
```

**NOTE**: Checkout the `default.yaml` since some steps are commented, for convenience.

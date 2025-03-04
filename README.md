# eBPF on MacOS - Actually on Lima

If you've never heard of [Lima](https://lima-vm.io/), it allows one to spawn virtual machines on MacOS.

For installation, check the [Lima docs](https://lima-vm.io/docs/installation/).

For MacOS, you are also gonna need QEMU. For installation check the [QEMU docs](https://www.qemu.org/download/#macos).

I find it pretty convenient, so I decided to show you how to run eBPF code with it. Or even better, give you the fully fledged eBPF development environment.

For this reason, there's a `default.yaml` file that you can utilize to create a VM - preconfigured to work with your eBPF programs, just by running:

```
limactl create --name=default default.yaml
limactl start default --timeout 30m
```

**NOTE**: The start up process takes quite a bit of time (~30min), so sit back and relax for a bit.
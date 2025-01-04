# bootc-on-osx

Testing of rhel bootc on top of osx as the hypervisor

## Secret setup

- `REGISTRY_PASSWORD`: quay.io password
- `FG_PAT`: temporary method for creating a release - Personal access tokens with sufficient rights to create a release and push to main

## Using mac os virtualization framework.

OSX has a inbuilt [hypervisor framework](https://developer.apple.com/documentation/bundleresources/entitlements/com.apple.security.hypervisor). There are multiple tools such as [`tart`](https://github.com/cirruslabs/tart) which have been built on top of it.
Thankfully [`libvirt`](https://libvirt.org/drvqemu.html) with Qemu can also use "`HVF`"

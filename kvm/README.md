KVM

kvm server на базе Virtual Box.

Включить вложенную виртуализацию:
```
VBoxManage modifyvm <VirtualMachineName> --nested-hw-virt on
```

----

За основу взят материал https://sumit-ghosh.com/posts/create-vm-using-libvirt-cloud-images-cloud-init/
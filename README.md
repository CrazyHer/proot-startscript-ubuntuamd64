# proot-startscript-ubuntuamd64
The proot latest build (v5.2.0-alpha-f0e3bfc5) and a script to run rootfs of Ubuntu on amd64

# Ubuntu Rootfs Images can be downloaded below:
https://mirrors.tuna.tsinghua.edu.cn/lxc-images/images/ubuntu/

# When you untar rootfs.tar.xz ....
```shell
./proot --link2symlink tar -xpf ubuntu.tar.xz -C ubuntu/

# Mono GTK# on Ubuntu Frame

Prerequisites:
- An Ubuntu Core 20 device or qemu

## Building the snap

You can build the snap using an lxd container with the following command.

    snapcraft --use-lxd

## Running on the device

Once your Ubuntu Core 20 device/qemu is up and running, please install ubuntu-frame to your UC20 device with;

    snap install ubuntu-frame

Transfer your built snap to UC20 device with scp and then install it with;

    snap install snap-name

Now, you should see your application up and running!

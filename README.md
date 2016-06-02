# ACME Remote Client utility

In order to control the main fonctionnalities of the ACME device, like :
- get informations about connected probes
- switch on/off probes
- reboot the system

This utility can control via XML-RPC a Yocto Poky based ACME Beaglebone Black device.

## Commands specifications

The commands are :

```
acme-cli help
```

Will get the supported commands from the ACME device.

```
acme-cli info <probe>
```

Will output informations about a connected probe id.

```
acme-cli switch_on <probe>
```

Will switch the corresponding probe On

```
acme-cli switch_off <probe>
```

Will switch the corresponding probe Off

```
acme-cli system_reboot
```
Will trigger a Beaglebone System software reset.

```
acme-cli version
```

Will get the current pyacmed implemented version on the ACME system image.

# PIA-EdgeRouter4
Setup PIA VPN on EdgeRouter 4

## Make Directory for the VPN Start Script:

```
mkdir /volume1/scripts/
```

## Edit VPN Start Script:

```
vi vpnc_connecting
```

## Copy and Paste below into vpnc_connecting

```
cp /volume1/scripts/vpnc_connecting /usr/syno/etc/synovpnclient/
/usr/syno/bin/synovpnc connect --id=o1612656128 --retry=3 --interval=30
```

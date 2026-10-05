Downgrades default fedora tls policy
```
nmcli connection modify eduroam 802-1x.phase1-auth-flags 0x20
nmcli connection modify eduroam 802-1x.phase1-auth-flags tls-1-0-enable,tls-1-1-enable
nmcli --ask connection up eduroam
```

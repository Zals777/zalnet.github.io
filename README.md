##################################################
### QR Code scanner for login hotspot MikroTik ###
################### Cara pakai ###################

1. Tambahkan button di login.html
```
<button onclick="window.location='zalnet.github.io';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip
add action=accept comment="Zals QR Code Scanner" disabled=no dst-host=zalnet.github.io
```
##################################################
##################################################

# Speedtest-server
This is repository of script for server (VPS/Baremetal) bandwidth speedtesting. The script focuses on local(Indonesian) servers, and some International Cities.

# User Guide
Run this command ~~

```bash
wget -qO- https://raw.githubusercontent.com/m-ihb/speedtest-server/master/script.sh | bash
```

or

```bash
curl -Lso- https://raw.githubusercontent.com/m-ihb/speedtest-server/master/script.sh | bash
```

The result out put will be as the following:

...

# To ADD or to REMOVE the speedtest servers 

Clone this repository, and edit the `script.sh` files, you can search the server's id number from this page: [Speedtest List Server](https://williamyaps.github.io/wlmjavascript/servercli.html)

The code line(s) that needs to be editted:

```bash
speed() {
    speed_test '' 'Speedtest.net'
    speed_test '7582'  'Telkom JKT-Indihome-ID'
    speed_test '12807' 'CBN JKT  ID'
    speed_test '797'  'Biznet Networks  JKT ID'
    speed_test '8579' 'Biznet Gio  JKT'
    speed_test '11118' 'MyRepublic Indonesia JKT'
    speed_test '6612' 'First Media JKT'
    speed_test '13954' 'MNC Play Media JKT'
    speed_test '3822' 'PT Telkomsel - JKT'
    speed_test '10730' 'PT XL Axiata Tbk - JKT'
    speed_test '4764' 'Indosat IM3-JKT'
    speed_test '4210' 'PT Smartfred Telecom JKT'
...
}
```




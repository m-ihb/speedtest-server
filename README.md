# speedtest-servers
this is repository of script for server (VPS/Baremetal) speedtesting

# How To Use

Run this command ~~

```bash
wget -qO- https://raw.githubusercontent.com/m-ihb/speedtest-servers/master/script.sh | bash
```

or

```bash
curl -Lso- https://raw.githubusercontent.com/m-ihb/speedtest-servers/master/script.sh | bash
```

The result should be like this:

[![A youtube video of BALITA cartoon](https://img.youtube.com/vi/AAh-0Ij4vVY/maxresdefault.jpg)](https://www.youtube.com/watch?v=AAh-0Ij4vVY)]

![](https://cdn-blinux.s3-id-jkt-1.kilatstorage.id/post/leon/result-speed.png)

# Change the speedtest server

First you need to clone this repository, and edit the `script.sh` files, you can search the servers id from this page: [Speedtest List Server](https://williamyaps.github.io/wlmjavascript/servercli.html)

The line that you must edit:

```bash
speed() {
    speed_test '' 'Speedtest.net'
    speed_test '7582'  'Telkom JKT    ID'
    speed_test '797'  'Biznet  ID'
    speed_test '5935' 'My Republic  SG'
    speed_test '4802' 'FirstMedia  ID'
    speed_test '12807' 'CBN JKT  ID'
    speed_test '16398' 'CN Mobile   CN'
    speed_test '3242'  'Netherland   NL'
    speed_test '14623' 'Japan      JP'
}
```

**Note:** Change the number with server id.



# Simple UP Test
>Remember to enable gtp5g kernel module first!
## Description

## Steps
* install flow rules
```
# under root folder of libgtp5gnl
./run.sh UPF_PDR_FAR_QER
```

* (Optional) enable tcpdump
```
export DUMP_NS=1
```

* run test
```
./run.sh SimpleUPTest
```
If you enable tcpdump, the pcap file will saved under scrpit/

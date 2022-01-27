# Outline
- Instance: `Standard F16s v2 (16 vcpus, 32 GiB memory)` with accelerated networking
- Data disk: `Performance tier: P60 - 16000 IOPS, 500 MBps`
- Tests using FIO: https://docs.microsoft.com/en-us/azure/virtual-machines/disks-benchmarks#fio
- Disk partitioned following: https://docs.microsoft.com/en-us/azure/virtual-machines/linux/attach-disk-portal#partition-a-new-disk

# Results
- Data disk: `WRITE: bw=61.8MiB/s (64.8MB/s)`
- Temp disk: `WRITE: bw=128MiB/s (134MB/s)`

# open-air-ran

## Run commands
### CU/DU split
To run CU
```
sudo ./nr-softmodem -O ../../../targets/PROJECTS/GENERIC-NR-5GC/CONF/cu_gnb.conf --sa --thread-pool 8,9,10
```
To run DU
```
sudo ./nr-softmodem -O ../../../targets/PROJECTS/GENERIC-NR-5GC/CONF/du_gnb.conf --sa --thread-pool 11,12,13,14,15
```
### Monolithic RAN
```
sudo ./nr-softmodem -O ../../../targets/PROJECTS/GENERIC-NR-5GC/CONF/gnb.sa.band78.273prb.fhi72.4x4-liteon.conf --sa --thread-pool 11,12,13,14,15
```

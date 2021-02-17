# roger-skyline-1

## Deployment
Clone the repository to the VM:
```
git clone https://github.com/KseniiaPrytkova/roger-skyline-1
```
Execute the deployment script (must be done with sudo):
```
$ chmod +x ./deploy.sh
$ sudo ./deploy.sh
```
Test that the deployment went fine by logging in to `192.168.10.42://login.html` on the host machine browser.

To get a checksum of the VM disk, go to /home/admin/VirtualBox VMs/, select the VM and then run:
```
$ shasum < [vdi file]
```

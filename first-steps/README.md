# First steps

## Finding images
```
az vm image list -p "Canonical"
az vm image list -p "Microsoft"
```


Procedure
A Disk for VM storage
A Network interface which can give us a Private and Public IP address
Attached to the network interface:
      A Network Security Group to allow SSH access to our VM
      A Public IP address
      

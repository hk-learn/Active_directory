# install vms

1. install the windows server os as a base server
2. install the windows 11 machine and name as a maintanance machine

installing the domain controller 

1. use sconfig 
    - change the ip address and the gateway
    - change the dnns ip address.
2. install the AD
    - shell
      install-windowsfeature ad-domain-services -includemanagementtools
# Firewall & IDS Lab {#firewall-ids}

## Network IP Configuration

| Device          | Interface | IP Address      |
|-----------------|-----------|-----------------|
| Metasploitable  |           | 192.168.56.102  |
| PfSense         | WAN       | 192.168.56.103  |
| PfSense         | LAN       | 192.168.1.1     |
| Kali (Client)   |           | 192.168.1.100   |


## Machines Deployment
### Pfsense
<p align="center">
  <img src="image1.png">
</p>
<p align="center">
  <img src="image2.png">
</p>

### Metasploitable
<p align="center">
  <img src="image22.png">
</p>

### Kali
<p align="center">
  <img src="image3.png">
</p>

## pfsense configuration
### interface assignment
<p align="center">
  <img src="image4.png">
</p>

### firewall rule configuration
<p align="center">
  <img src="media/image5.png">
</p>
<p align="center">
  <img src="image6.png">
</p>

### Testing the configuration
<p align="center">
  <img src="image7.png">
</p>
<p align="center">
  <img src="image8.png">
</p>

## Installing snort
<p align="center">
  <img src="image9.png">
</p>

## configure snort
<p align="center">
  <img src="image10.png">
</p>

MultiAV: Extended
=======================
Combine the awesome approaches of blacktop's av docker plugins with joxeankoret's MultiAV! Pure simplicity and pythonness! Autoscale support for huge scan tasks using docker-machine included!

**Quicklinks:**
- [QuickStart Guide](https://github.com/danieljampen/multiav/wiki/QuickStart-Guide)
- [Configuration Documentation](https://github.com/danieljampen/multiav/wiki/Configuration)
- [REST API Documentation](https://github.com/danieljampen/multiav/wiki/REST-API)

## Key Features

* **Quick installation** - No AV installation required, everything is handled by MultiAV and is powered by docker containers
* **Easy integration** - Access via web interface, REST API or python client
* **Secure by design** - All engines operate in isolated docker containers preventing access the samples to gain access to the infrastructure
* **Stay in control of your samples** - No leaks to AV vendors by design
* **Reproducible, reliable results** - Reports specially designed to contain all information required to reproduce scan results
* **Effortless updating** - One click AV engine update, guarantee that the shown av versions are used for scans (no unnoticed updates possible by design)
* **Multiple scanning strategies** - define how your scans are executed / scheduled. Locally, Locally with a global limit or using the powerfull **auto scaleing system** supporting 17 hypervisors and cloud computing services
* **Scan samples with 13 AV plugins**:
  * Windows Defender - Repo: [here](https://github.com/malice-plugins/windows-defender)
  * Sophos - Repo: [here](https://github.com/malice-plugins/sophos)
  * Avast[**Requires License**] - Repo: [here](https://github.com/malice-plugins/avast)
  * Avg - Repo: [here](https://github.com/malice-plugins/avg)
  * BitDefender - Repo: [here](https://github.com/malice-plugins/bitdefender)
  * ClamAV - Repo: [here](https://github.com/malice-plugins/clamav)
  * Comodo - Repo: [here](https://github.com/malice-plugins/comodo)
  * DrWeb - Repo: [here](https://github.com/malice-plugins/drweb)
  * EScan - Repo: [here](https://github.com/malice-plugins/escan)
  * FProt - Repo: [here](https://github.com/malice-plugins/fprot)
  * FSecure - Repo: [here](https://github.com/malice-plugins/fsecure)
  * Kaspersky[**Requires License**] - Repo: [here](https://github.com/malice-plugins/kaspersky)
  * McAfee - Repo: [here](https://github.com/malice-plugins/mcafee)
* **Gain additional information using 7 Intel, File format or Metadata plugins**:
  * FileInfo (exiftool, TRiD and ssdeep) - Repo: [here](https://github.com/malice-plugins/fileinfo)
  * Yara - Repo: [here](https://github.com/malice-plugins/yara)
  * ShadowServer - Repo: [here](https://github.com/malice-plugins/shadow-server)
  * VirusTotal - Repo: [here](https://github.com/malice-plugins/virustotal)
  * NationalSoftwareReferenceLibrary - Repo: [here](https://github.com/malice-plugins/nsrl)
  * PEScan - Repo: [here](https://github.com/malice-plugins/pescan)
  * Floss - Repo: [here](https://github.com/malice-plugins/floss)

## MultiAV: Extended in Action
### Sample Upload Page

![multiav-upload](https://raw.githubusercontent.com/danieljampen/multiav/master/docs/images/multiav-upload.png)

### Scan Result Live Tracking

![multiav-scan-running](https://raw.githubusercontent.com/danieljampen/multiav/master/docs/images/multiav-scan-running.png)

### Search the Report DB

![multiav-search](https://raw.githubusercontent.com/danieljampen/multiav/master/docs/images/multiav-search.png)

### Live System Overview

![multiav-autoscale-overview](https://github.com/danieljampen/multiav/blob/master/docs/images/multiav-autoscale-overview.png)

### Update AntiVirus Engines
**Update in progress**
![multiav-update-in-progress](https://github.com/danieljampen/multiav/blob/master/docs/images/multiav-update-in-progress.png)
**Update complete**
![multiav-update-complete](https://raw.githubusercontent.com/danieljampen/multiav/master/docs/images/multiav-update-complete.png)

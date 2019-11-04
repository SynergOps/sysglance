# Sysglance

Syglance is a simple and universal, Linux utility for generating a report for the host system
![Screenshot](assets/sysglance-screenshot.png?raw=true "Parcial Screenshot")

# Features

Sysglance will generate a report about:

- Host information
- System uptime and load in 1, 5 and 15 minutes span
- Available User Accounts
- Currently logged in users
- CPU, GPU, USB, Network adapters
- File system partitions and disk space usage
- Free and used memory in the system
- Top 10 processes as far as memory usage is concerned including user, pid and when it started
- Show per Network device, Public and Private IP addresses
- List of Processes and open Networking Ports
- List of Errors/Alerts in log files since the last system boot


## Installation

[![Build Status](https://travis-ci.org/Utappia/sysglance.svg?branch=master)](https://travis-ci.org/Utappia/sysglance)

Sysglance is packaged as AppImage using Travic CI in continuous maner. 

You can download the latest version from [Releases](https://github.com/Utappia/sysglance/releases/tag/continuous) by clicking on **Assets** and the **Sysglance*.AppImage** file.

Or you can do it from terminal:

```bash
wget https://github.com/Utappia/sysglance/releases/download/continuous/Sysglance-x86_64.AppImage
```
Once downloaded you have to give the Sysglance package, executable permitions.
e.g.:

```bash
chmod +x Sysglance*.AppImage
```

## Usage

You can run Sysglance with

```bash
./Sysglance*.AppImage
```
Or you can save the output to a text file for further investigation

```bash
./Sysglance*.AppImage > sysglance-report.txt
```

## Stay up to date on releases

To get notified for new releases, you just need to click on Watch --> Releases Only :

![Notify](assets/notify-me-for-releases.png?raw=true "Notify new release")


## Contributing
### Code - Bug reports
Pull requests are welcome. For major changes, please [open an issue](https://github.com/Utappia/sysglance/issues) first to discuss what you would like to change.
Please make sure test your pull requests as appropriate.

### Donation
You can also contribute by clicking on the **Sponsor** button

## License
Please reffer to [LICENSE](https://github.com/Utappia/sysglance/blob/master/LICENSE) file

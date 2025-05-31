# TrueConf Server Free
TrueConf Server Free Messenger with Video Calls for Corporate Communications

- Enjoy video conferences in UltraHD
- Free version for up to 1,000 users
- On-premises server for Windows and Linux
- Client applications for all popular platforms
- Fully secure solution for corporate network

## How to install TrueConf Server Free?

TrueConf offers you an opportunity to take [full advantage](https://trueconf.com/features.html) of corporate video conferencing on various Linux-based operating systems. Only 64-bit versions of the OS are supported.

### Mandatory preliminary steps

- TrueConf Server contains its own web server. To prevent any possible conflicts or clashes, please deploy TrueConf Server on a computer running on Linux without a pre-installed web server.
- Add the user who will install TrueConf Server and get access to the TrueConf Server control panel to your OS. You can use the account that was created when installing your OS.
To install TrueConf Server successfully, please make sure that there is no OS user whose login or name is trueconf.

- Fill out all the fields in the [registration form](https://trueconf.com/downloads/trueconf-server/en).
- Click **Submit & Download** to receive your registration key on the email address you’ve specified.

The email containing your registration key will be sent within 15 minutes. If you cannot find the email containing your registration key in your inbox, please check the SPAM folder. You can also request the key via live chat or [contact us](https://trueconf.com/company/contacts.html) in any other way convenient to you.

To run the commands listed below on behalf of the administrator, use the **sudo** program. Please note that by default **sudo** may not be available on your OS. To check if it is available, run the command `sudo -V`. If this program is not available, install it following the guide for your OS.

### Windows

Installing TrueConf Server on Windows is the same as installing a regular application for this operating system. If you encounter difficulties, [read this article](https://trueconf.com/blog/knowledge-base/get-video-conferencing-system-15-minutes).

### Linux

Installing TrueConf Server on Linux is no different from installing a regular application for this operating system. If you encounter difficulties, [read this article](https://trueconf.com/blog/knowledge-base/install-and-set-up-your-video-conferencing-server-for-linux-in-15-minutes).

#### Debian

Download the file for your OS. Proceed to the directory with downloaded TrueConf deb-package and start the installation by running the following command in the admin mode:

```
sudo apt install -yq ./trueconf-server-name.deb
```

where `trueconf-server-name.deb` is the name of the installation package.

During installation you will see the input field for entering the logins of those OS users who will be allowed to access the control panel as administrators. Enter the login of the user created before. It is possible to specify multiple logins (separated by commas) at the same time.

#### CentOS

Regardless of the installation method, you will need to take these preliminary steps:

- Disable SELinux, the system that controls process access to OS resources. To do it, execute this command as the administrator:

```
sudo sed -i 's/^SELINUX=.*/SELINUX=disabled/g' /etc/selinux/config
```

- Connect the EPEL repository by running this command as the administrator:

```
sudo dnf install epel-release
```
Only at this point, one can install TrueConf Server. Next download the file from release page. Go to the directory where the downloaded rpm package is stored. Next, run this command as the administrator to install the package:

```
sudo dnf install -y trueconf-server-name.rpm
```

where `trueconf-server-name.rpm` is the name of the installation package.

During installation you will see the input field for entering the logins of those OS users who will be allowed to access the control panel as administrators. Enter the login of the user created before. It is possible to specify multiple logins (separated by commas) at the same time.

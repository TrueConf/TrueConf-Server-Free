# TrueConf Server Free: Secure Video Conferencing System and Corporate Messenger for 1000 Users

##Description

TrueConf Server Free is an all-in-one corporate communications platform with a built-in messenger, video conferencing, and collaboration tools.

## Features

TrueConf Server Free offers the following features:

* Support for native client applications on all popular operating systems, including mobile devices. 
* 4K video conferences.
* **Up to 1,000 chat participants**.
* Collaboration tools (content sharing, screen annotation, slideshow).
* Private and group chats.
* Address book and presence statuses.
* Secure file storage.
* Call history and chat syncing across all devices.
* LDAP integration.

<p align="center"><a href="https://github.com/TrueConf/TrueConf-Server-Free/releases/"><img src="./images/download.svg" width="200"></a></p>

### Video conferencing

Schedule meetings or escalate your chats into video conferences on the fly, create events with up to 2000 participants.

<p align="center"><img src="./images/participants.png" width="600px"></p>

Take full advantage of AI features:

* Noise suppression.
* Background blurring and virtual backgrounds.
* Conference branding.
* Meeting transcription (*integration with TrueConf AI Server is needed*).

Feel free to receive calls and participate in conferences on any device — chat history will be synced automatically.

Join online meetings on TrueConf Server Free using a browser and an invitation link.

<p align="center"><img src="./images/multi_device.png" width="600px"></p>

### Corporate messenger

In addition to the core features, private and group chats support text formatting which helps you to highlight important points.

Use keyboard shortcuts and drag-and-drop for quick chat interaction. Besides, the built-in viewer will make it much easier to work with media content.

Mention group chat participants to draw their attention to your message.

<p align="center"><img src="./images/chats.png" height="400px"></p>

### Collaboration without borders

TrueConf application offers a wide range of collaboration tools. 

Ability to share different types of content: 

* Desktop.
* Individual screen (if multiple monitors are available).
* Individual application windows (including CAD models or presentations).
* Slideshows.

You can stream audio separately or while sharing any type of content.

<p align="center"><img src="./images/tools.png" width="600px"></p>

### Share content in high quality

Share content in 4K UltraHD during online meetings! Show high-definition CAD models, spreadsheets, and presentations created in third-party apps.

<p align="center"><img src="./images/content.png" width="600px"></p>

### Flexible conference management

Manage devices and adjust participants’ layouts in two clicks depending on the meeting scenario.


<p align="center"><img src="./images/layout.png" width="600px"></p>

## TrueConf Server workflow

The following diagram shows how TrueConf Server interacts with other TrueConf solutions and third-party services (some integrations are not available in the Free version, more details are given below):

<p align="center"><img src="./images/scheme.png" width="1000px"></p>

## Comparison of TrueConf Server Free and TrueConf Server 

|<!-- -->  |TrueConf Server Free | TrueConf Server |
|:---------|:-------------------:|:---------------:|
| Group video conferences, moderated role-based conferences, and online lessons in 4K UltraHD quality. | Up to 10 participants in one conference | Up to 2000 participants in one or several conferences depending on the terms of your license.  |
| Audio and video calls between two users in 4K UltraHD quality. | Up to 1000 users  | V |
| Private and group chats, file sharing, and secure data storage. | Up to 1000 users    | V |
| Slideshow, content sharing, polling, reactions, and much more. | V | V |
| Client applications for all platforms: Windows, Linux, macOS, iOS, Android, and Android TV. | V | V |
| Ability to sign in and work on multiple devices. | V | V |
| Presence statuses which show whether users are currently available and what type of device they have.  | V | V |
| Ability to schedule conferences in the calendar.  | V | V |
| Recording video conferences locally in client applications and centrally on the server side. | V | V |
| Management of integrations, accounts, groups and their permissions, ability to schedule, record, and manage conferences in the built-in web interface.  | V | V |
| No limit on the number of accounts. | V | V |
| Works through NAT, Firewall, and Proxy. No need to use a public IP address or open an additional port.  | V | V |
| Stable performance on weak channels and devices. Сall quality will be automatically adjusted depending on changing connection conditions and endpoint devices. | V | V |
| Full compatibility with classic hardware endpoints thanks to the built-in SIP/H.323 gateway. | One connection. | V |
| Invitations to conferences for mobile devices and landline phone users, integration with VoIP telephony and PBXs. | V | V |
| Web conferences that can be joined from a browser. Fully-featured browser-based  communication without plugin installation thanks to WebRTC support. | 1 guest connection.  | V |
| Installation within the corporate LAN/VPN network. | V | V |
| Connection to Zoom ®, Cisco Webex, GoToMeeting, and Skype for Business conferences. | V | V |
| Integration with LDAP directories (e.g., Active Directory), user information synchronization, single sign-on (SSO) for all users of the video conferencing server. | V | V |
| TrueConf Server API, video communication integration with third-party solutions, services, and automation tools. | V | V |
| TrueConf SDK. Integration of video communication into third-party applications. | X | V |
| Manual distribution of PRO licenses. | X | V |
| Autonomy. There is no need for the video conferencing server to be constantly connected to the Internet.  | X | V |
| Conference streaming. Stream your conferences to third-party services and solutions (YouTube, Wowze, etc.) to reach any audience.   | X | V |
| Federation support, communication with the  users of TrueConf Server instances installed by other customers. | X | V |
| Support for UDP Multicast, video conferences and data exchange via satellite networks which helps to reduce the load on the video conferencing server. | X | V |
| Guaranteed technical support. | X | V |

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

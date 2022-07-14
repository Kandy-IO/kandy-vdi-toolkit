# @kandy-io/kandy-vdi-toolkit
## Kandy VDI toolkit

In conjunction with the Kandy JavaScript SDK, the Kandy Distant Toolkit provides a platform that enables application developers to deliver a HD experience for video and audio calls in VDI environments. The platform hides the complexities of dealing with thin clients and server-based computing so that application developers can focus on user capabilities and user experience.

The Kandy JavaScript SDK works with the Kandy Distant Toolkit to coordinate the application behavior on the VDI Desktop and the media processing on the thin client.

The Kandy VDI Toolkit separates out the application from the media processing, enabling the application to be securely deployed in the managed environment while not impacting performance by running the media between the thin client and the virtual desktop.

The Toolkit is currently supported on thin clients running eLux OS for use with Citrix Worspace App, using the [Kandy Distant Driver for VDI](https://github.com/Kandy-IO/kandy-distant-vdi/).

Some of the libraries within this toolkit:

#### [Kandy HID Driver for VDI](https://github.com/Kandy-IO/kandy-hid-vdi/)

Enables the use of HID devices in a Citrix VDI environement

#### [Kandy Distant Driver for VDI](https://github.com/Kandy-IO/kandy-distant-vdi/)

Enables application developers to deliver a HD experience for video and audio calls in a Citrix VDI environment

#### [Kandy Distant JS](https://github.com/Kandy-IO/kandy-distant-js/)

Enables session-based communication over Citrix Virtual Channels

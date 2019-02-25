<!-- mdformat off(GitHub header) -->
Grab n Go Loaners Recommended Best Practice Guides
======
<!-- mdformat on -->

<p align="center">
  <a href="#grabngo--">
    <img src="https://storage.googleapis.com/gngloaners/gnglogo.png" alt="Grab n Go Icon" />
  </a>
</p>

The Grab n Go (GnG) Loaner project is a fully automated loaner management suite
that manages enterprise enrolled Chrome OS devices by automatically assigning,
returning, and monitoring these devices.

Using this guide and the files provided in this repository will ensure a smooth and
working deployment. 

## Before attempting to Deploy GnG. Please make sure you have the following:

*   An enterprise G Suite domain
*   A Google App Engine (GAE) application
*   A Chrome App that runs on each Chrome OS device

## Need to have programs; Mac, Linux, or a Windows machine is usable. The following  programs need to be installed:

*	Google SDK-[Windows](https://dl.google.com/dl/cloudsdk/channels/rapid/GoogleCloudSDKInstaller.exe),[MAC](https://cloud.google.com/sdk/docs/downloads-interactive#mac),[Linux](https://cloud.google.com/sdk/docs/downloads-interactive#linux).
*	Git- [Windows](https://git-scm.com/download/win),[MAC](https://git-scm.com/download/mac),[Linux](https://git-scm.com/download/linux).
*	
*	

## Deploying GnG 
GnG Deployment can be done in 3 phases as long as the above pre-requisites have been met. 

### Preparing our Google Cloud Backend
The heart of GnG is hosted on Google Cloud and where all the devices report and recieve 
information from 

```
git clone -b Alpha-\(0.7\) https://github.com/google/loaner.git
cd loaner
```

* To discuss this project send an email to loaner@googlegroups.com.
* Read more about releases in our [release notes](docs/release_notes.md).
* Please file bugs using the GitHub issue tracker.


#### Reference Documentation

-   [Grab n Go APIs](docs/gng_apis.md)
-   [User Guide](docs/user_guide.md)
-   [Frequently Asked
    Questions](docs/faq.md)

## Contributing

We are not accepting external contributions at this time. The current release of
the application is still in alpha. We will be actively contributing to this
project throughout 2018. After this project reaches a 1.0 release, we will begin
accepting external contributions. Please feel free to file bugs and feature
requests using [GitHub's Issue
Tracker](https://github.com/google/loaner/issues).

## Disclaimers

The current release of the application is in active development.

This is **not** an official Google product. This program is not formally
supported and the code is available as-is with no guarantees.

Documentation, including those for end users of this system, is provided in this
repository only as examples of the "out of box" experience for the app and does
not account for any modifications made by the administrator in deploying the
app. Administrators should review and adjust all documentation and instructions
found in the app as applicable to their deployment.
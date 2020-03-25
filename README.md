# iPadForGranny
Collection of information and software to set up computers for elderly users. Make it simple. Reduce it to the minium. If possible make everything work on older hardware/software since it's less likely that newst hardware/software is available.

## General
### iPad/iPhone Feature reduction
You can setup an iPad in **supervised mode** and disable a lot of features and remove stuff not generally required. For example you can only show certain Apps on the device or disable changing critical settings.
Supervised mode and configuring the devises is possible with [Apple Configurator] (https://apps.apple.com/de/app/apple-configurator-2/id1037126344?mt=12). For the initial setup it is necessary to have physical access. It is possible to change settings later on over-the-air using a MDM System (Mobile Devive Management). These systems are generally developed/used for "the Enterprise" IT. But free solutions exist. e.G. [jamfnow](https://www.jamf.com/pricing/) is free for the first 3 devices. 

[Tutorial (in German) How-To setup supervised mode](https://www.youtube.com/watch?v=4emdDAedGQo&feature=youtu.be)

## Usecases
### Calling / Videochat
#### Facetime
You can add Web-Clips to dial certain users directly with the URL Scheme facetime://<number>.
  
Example:
  
    facetime://thorsten@foo.bar
  
Unfortunately* you still get a pop-up where the granny again has to commit that she wants to start a call. (*: It's a good idea from a security perspective)

#### Signal
There exists a sgnl:// URL scheme on iOS. No tests so far.

## Photo Sharing

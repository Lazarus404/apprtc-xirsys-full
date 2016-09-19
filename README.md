[![Build Status](https://travis-ci.org/webrtc/apprtc.svg?branch=master)](https://travis-ci.org/webrtc/apprtc)

# AppRTC Demo Code (XirSys - FULL)

## Note

This version of the web AppRTC application is currently being modified to use the XirSys ICE endpoint and signalling.

THIS VERSION DOES NOT YET WORK!

For a version of AppRTC that uses XirSys ICE, please clone [https://github.com/xirdev/apprtc-xirsys-ice](https://github.com/xirdev/apprtc-xirsys-ice)

## Development

This repo is based on the example AppRTC app in the [WebRTC repo](https://github.com/webrtc) but has / will undergo many bigger changes.  This is because the AppRTC web application and associated mobile applications use the Python built socket layer internal to the application.  This application is being redeveloped from the AppRTC source to use the XirSys signalling layer.  This means much of the project source is / will be dumped and alternative features will be added.  However, the structure of the application, the libraries it uses and the deployment requirements of the application will be preserved where possible.  This allows the application to be a drop in for the Google AppRTC variant with less resource requirements on the Google App Engine infrastructure.

For more information, please email [experts@xirsys.com](mailto:experts@xirsys.com)

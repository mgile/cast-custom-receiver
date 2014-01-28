# cast-custom-receiver-sample

This Google Cast demo application shows how to cast videos from an Android device in a way that is fully compliant with the UX Guidelines. 

## Dependencies
* (Optional) NodeJS (http://nodejs.org)
* A Google Cast Receiver Device (eg. Chromecast)

## Setup Instructions
* You will need a Google Cast device such as a Chromecast to run this sample code
* Register your Cast device Developer Console ((http://cast.google.com/publish) to allow it to run this sample
* Register a custom receiver application on the Cast Developers Console (http://cast.google.com/publish). The URL to use will be the IP address of the system you will run the receiver server from. If you run the server using the provided NodeJS server on your local machine, enter the ip-address of your computer with it's non local IP (eg. http://172.17.21.148:9999/sample_media_receiver.html). You will get an App ID when you finish registering your application.
* Setup the project dependencies
* Run the provided NodeJS server script using NodeJs or deploy to an existing server

## Project Setup (Optional)
* Install NodeJS (http://nodejs.org/) for your platform
* In the root of this project execute
* $> npm install express
* $> node s3.js
* Receiver will be available on http://IP-Address:9999/sample_media_receiver.html which should be the URL for your registered application in the Developer Console

## Documentation
The source is heavily documented and for additional reference please refer to the Receivers section of the Google Cast documentation.

## References and How to report bugs
* Cast APIs: http://developers.google.com/cast/docs
* Design Checklist (http://developers.google.com/cast/docs/design_checklist)
* If you find any issues, please open a bug here on GitHub

## How to make contributions?
Please read and follow the steps in the CONTRIBUTING.md

## License
See LICENSE
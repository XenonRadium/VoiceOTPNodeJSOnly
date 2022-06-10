# VoiceOTPNodeJSOnly

This program sends a programmable voice payload to callee number specified within the Javascript code.
The payload contains a brief message followed by a random 6 digit number (placeholder for OTP) to the callee number.
Deployment of the Twilio app requires Twilio CLI commands run in Windows Powershell.

twilio serverless:deploy is required to be run everytime a change is made to the Javascript code.
Once the command is run, a HTTPS url is generated that can be used to activate function via POST protocol. Postman is recommended
to fulfill this function.

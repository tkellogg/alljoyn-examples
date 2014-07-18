
AllJoyn Java Samples for Android README
---------------------------------------

This directory contains the following set of AllJoyn usage samples:


**simple** -      This sample shows how to connect to a local AllJoyn daemon in 
              order to publish an AllJoyn object that implements a very simple
              interface. The sample also shows how to connect to the local
              daemon in order to execute a method on the published object.

**secure** -      This sample shows how to enable authentication and encryption for
              the simple sample.  The service supports multiple authentication
              mechanisms.  Each client supports one of the authentication
              mechanisms. Most of the fun is here:
              https://github.com/tkellogg/alljoyn-examples/blob/master/secure/service/src/org/alljoyn/bus/samples/secureservice/

**properties** -  This sample shows how to use AllJoyn properties in an AllJoyn interface.

**chat** -        This sample shows how to use discovery to connect with other
              devices.

**contacts** -    This sample shows how to use AllJoyn methods to send complex data
              types.


[SlideShare Presentation Here](http://www.slideshare.net/kellogh/security-identity-in-alljoyn-1406)

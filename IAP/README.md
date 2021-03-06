
IAP - Internet Application Protocal
http://tutorials.jenkov.com/iap/index.html

What Does IAP Mean?

IAP is an acronym for Internet Application Protocol. However, during the early design stages we used the pseudonym "Intelligent Agent Protocol" because we had intelligent agents in mind when we started. Since then we have broadened the focus of the protocol to be a general purpose protocol rather than a protocol targeted at a specific niche.

IoT and Web 3.0

With the Internet of Things (IoT) we will have a lot more different devices communicating via the internet. Different devices send and receive different types of data, and have different communication patterns. A new network protocol should take that into account.

Similarly the next generation of the web, being it Web 3.0 or Web 4.0 (or whatever name it gets), will most likely add new types of data and communication patterns to the ones already existing. A new network protocol should attempt to take that into consideration too.

We have attempted to address these challenges with IAP. First of all, IAP contains a very flexible data format at its core. This data format contains predefined structures for the most commonly used data types, but allows for custom data types when these are not sufficient. In the worst case a device can default to just sending raw bytes and let it be up to the communicating parties to make sense of them.

Second, IAP allows different semantic protocols to run embedded within IAP. The IAP specification will predefine a set of semantic protocols for common tasks, but an application can define its own semantic protocol if none of the predefined semantic protocols suffice.

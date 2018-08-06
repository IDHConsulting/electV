# electV

Create and manage electronic vouchers and coupons

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Java	Java is the fundamental platform on which all the POS components (Core, VAS, EFT) are built. Minimum version required: Java 1.8	

JavaFx	JavaFx (included with Java SE from version 1.8) is the GUI technology used to port the POS GUI interface from Java.AWT	

JavaPos	JavaPos is the Java implementation of the UnifiedPOS specification. It provides an abstraction layer between the POS application and the connected peripheral de-vices, such as the printer, MSR, etc.	

HyperSQL	HSQLDB is the light-weight, embedded database which will be used for all the ported data structures	

Log4J	Log4J v2 will be used by all the components, to pro-vide improved logging with features like Rolling log files	

Apache Tomcat	Apache Tomcat is the Servelet container that will host the VAS portal web application component	

JSON	JSON will be used extensively as the base format for all API message communications between local and remote components. And for refactored data struc-tures associated with specific POS data, such as the new Tlog	

XML	XML will be used for legacy data structures associat-ed with specific POS data, such as Products, Promo-tions and Customers	

REST	REST styled API will be used for all web-services	

Rudder	Rudder Agent will be installed on each node, to ena-ble Application Deployment Automation and Monitor-ing through the use of the Rudder and CFEngine plat-form.	

## Deployment

Consult the deployment guide for full instructions.

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/IDHConsulting/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **IDH Consulting** - *Initial work* - [IDH Consulting]

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under GPLv3 license, see the provided "LICENSE" file or http://www.gnu.org/licenses/gpl-3.0.txt

## Acknowledgments



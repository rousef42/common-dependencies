[![License](https://img.shields.io/badge/License-EPL%201.0-red.svg)](https://opensource.org/licenses/EPL-1.0)
[![Build Status](https://travis-ci.org/dellemc-symphony/common-dependencies.svg?branch=master)](https://travis-ci.org/dellemc-symphony/common-dependencies)
[![Slack](http://img.shields.io/badge/slack-join%20the%20chat-00B9FF.svg?style=flat-square)](https://codecommunity.slack.com/messages/symphony)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.dell.cpsd/common-dependencies/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.dell.cpsd/common-dependencies)
[![Semver](http://img.shields.io/SemVer/2.0.0.png)](http://semver.org/spec/v2.0.0.html)

# common-dependencies
## Description

This repository contains common dependencies and their retrospective versions required by the Project Symphony repositories.
It is included by some Project Symphony repositories and includes (but is not limited to) the following dependencies:
- Spring dependencies
- Jackson dependencies
- Google dependencies
- logging dependencies
- JSON dependencies
- persistence dependencies
- commons dependencies
- web dependencies
- JCommander dependencies
- documentation dependencies
- test dependencies

For the full list of dependencies, refer to pom.xml.

## Documentation
You can find additional documentation for Project Symphony at [dellemc-symphony.readthedocs.io][documentation].
## Before you begin
Verify that the following tools are installed:
 
* Apache Maven 3.0.5+
* Java Development Kit (version 8)
## Building
Run the following command to build this project:
```bash
mvn clean install
```
## Contributing
Project Symphony is a collection of services and libraries housed at [GitHub][github].
 
Contribute code and make submissions at the relevant GitHub repository level. See [our documentation][contributing] for details on how to contribute.
## Community
Reach out to us on the Slack [#symphony][slack] channel by requesting an invite at [{code}Community][codecommunity].
 
You can also join [Google Groups][googlegroups] and start a discussion.
 
[slack]: https://codecommunity.slack.com/messages/symphony
[googlegroups]: https://groups.google.com/forum/#!forum/dellemc-symphony
[codecommunity]: http://community.codedellemc.com/
[contributing]: http://dellemc-symphony.readthedocs.io/en/latest/contributingtosymphony.html
[github]: https://github.com/dellemc-symphony
[documentation]: https://dellemc-symphony.readthedocs.io/en/latest/

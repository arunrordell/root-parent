[![License](https://img.shields.io/badge/License-EPL%201.0-red.svg)](https://opensource.org/licenses/EPL-1.0)
[![Build Status](https://travis-ci.org/dellemc-symphony/root-parent.svg?branch=master)](https://travis-ci.org/dellemc-symphony/root-parent)
[![Slack](http://community.codedellemc.com/badge.svg)](https://codecommunity.slack.com/messages/symphony)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.dell.cpsd/root-parent/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.dell.cpsd/root-parent)
[ ![Download](https://api.bintray.com/packages/dell-emc-cpsd/git-hub/root-parent/images/download.svg?version=0.2.4) ](https://bintray.com/dell-emc-cpsd/git-hub/root-parent/0.2.4/link)
[![GitHub issues](https://img.shields.io/github/issues/dellemc-symphony/root-parent.svg)](https://github.com/dellemc-symphony/root-parent/issues?q=is%3Aopen+is%3Aissue)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/dellemc-symphony/root-parent.svg)](https://github.com/dellemc-symphony/root-parent/pulls?q=is%3Aopen+is%3Apr)
[![Semver](http://img.shields.io/SemVer/2.0.0.png)](http://semver.org/spec/v2.0.0.html)

# root-parent

## Description
This repository contains important base configuration settings and properties required by other Project Symphony repositories. 

It is included by default in every new Project Symphony repository and includes (but is not limited to) the following configurations:
- Maven AntRun
- Java Code Coverage Library
- Maven Docker
- Maven Failsafe 
- Maven Surefire
- Maven Gitflow
- Maven Javadoc
- Maven GPG
- Repository information for Maven Central

For configurations for a specific repository, refer to pom.xml.

## Documentation
You can find additional documentation for Project Symphony at [dellemc-symphony.readthedocs.io](https://dellemc-symphony.readthedocs.io).

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

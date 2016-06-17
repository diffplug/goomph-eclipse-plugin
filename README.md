# Gradle and Eclipse RCP

<!---freshmark shields
output = [
	link(shield('Latest version', 'latest', '{{stable}}', 'blue'), 'https://github.com/{{org}}/{{name}}/releases/latest'),
	link(shield('License Apache', 'license', 'Apache', 'blue'), 'https://tldrlegal.com/license/apache-license-2.0-(apache-2.0)'),
	link(shield('Changelog', 'changelog', '{{version}}', 'brightgreen'), 'CHANGES.md'),
	link(image('Travis CI', 'https://travis-ci.org/{{org}}/{{name}}.svg?branch=master'), 'https://travis-ci.org/{{org}}/{{name}}')
	].join('\n');
-->
[![Latest version](https://img.shields.io/badge/latest-1.0.0-blue.svg)](https://github.com/diffplug/gradle_and_eclipse_rcp/releases/latest)
[![License Apache](https://img.shields.io/badge/license-Apache-blue.svg)](https://tldrlegal.com/license/apache-license-2.0-(apache-2.0))
[![Changelog](https://img.shields.io/badge/changelog-1.0.0--SNAPSHOT-brightgreen.svg)](CHANGES.md)
[![Travis CI](https://travis-ci.org/diffplug/gradle_and_eclipse_rcp.svg?branch=master)](https://travis-ci.org/diffplug/gradle_and_eclipse_rcp)
<!---freshmark /shields -->

Based on a talk to be given at [Gradle Summit 2016](https://gradlesummit.com/schedule/gradle-and-eclipse-rcp).

## Acknowledgements

* Bugs found by [findbugs](http://findbugs.sourceforge.net/), [as such](https://github.com/diffplug/durian/blob/v2.0/build.gradle?ts=4#L92-L116).
* OSGi metadata generated by JRuyi's [osgibnd-gradle-plugin] (https://github.com/jruyi/osgibnd-gradle-plugin), which leverages Peter Kriens' [bnd](http://www.aqute.biz/Bnd/Bnd).
* Built by [gradle](http://gradle.org/).
* Tested by [junit](http://junit.org/).
* Maintained by [DiffPlug](http://www.diffplug.com/).

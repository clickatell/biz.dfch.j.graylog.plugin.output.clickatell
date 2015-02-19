biz.dfch.j.graylog.plugin.output.dfchBizClickatellOutputPlugin
==============================================================

Plugin: biz.dfch.j.graylog.plugin.output.dfchBizClickatellOutputPlugin

d-fens GmbH, General-Guisan-Strasse 6, CH-6300 Zug, Switzerland

This Graylog Output Plugin lets you send custom formatted short messages (SMS) via the Clickatell Messaging Provider and works with the upcoming version 1 of Graylog.

See [Graylog Clickatell Output Plugin v1](http://d-fens.ch/tag/graylog2/) and [Creating a Graylog Output Plugin](http://d-fens.ch/2015/01/07/howto-creating-a-graylog-output-plugin/) (v0.92.x) for further description on how to create plugins.

For your information: your build will FAIL the tests unless you specify a valid [API key](https://github.com/dfch/biz.dfch.j.graylog.plugin.output.clickatell/blob/f9d4d96543de16c56d18441c5fb87b60f333c3b1/src/test/java/biz/dfch/j/clickatell/rest/ClickatellClientTest.java#L33).

You can [download the binary](https://drone.io/github.com/dfch/biz.dfch.j.graylog.plugin.output.clickatell/files) [![Build Status](https://drone.io/github.com/dfch/biz.dfch.j.graylog.plugin.output.clickatell/status.png)](https://drone.io/github.com/dfch/biz.dfch.j.graylog.plugin.output.clickatell/latest) at our [drone.io](https://drone.io/github.com/dfch) account.

Getting started for users
-------------------------

This project is using Maven and requires Java 7 or higher.

* Clone this repository.
* Run `mvn package` to build a JAR file.
* Optional: Run `mvn jdeb:jdeb` and `mvn rpm:rpm` to create a DEB and RPM package respectively.
* Copy generated jar file in target directory to your graylog server plugin directory.
* Restart the graylog server.

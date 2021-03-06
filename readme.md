#### Issues
[![Stories in Progress](https://badge.waffle.io/FAForever/downlords-faf-client.png?label=in%20progress&title=In%20Progress)](https://waffle.io/FAForever/downlords-faf-client)
[![Stories in Ready](https://badge.waffle.io/FAForever/downlords-faf-client.png?label=Ready&title=Up%20For%20Grabs)](https://waffle.io/FAForever/downlords-faf-client)
#### master
[![Build Status](https://travis-ci.org/FAForever/downlords-faf-client.svg?branch=master)](https://travis-ci.org/FAForever/downlords-faf-client)
[![Coverage Status](https://coveralls.io/repos/FAForever/downlords-faf-client/badge.svg)](https://coveralls.io/r/FAForever/downlords-faf-client)

Please see the [project page](http://FAForever.github.io/downlords-faf-client/)

Please take a look at the [contribution guidelines](https://github.com/FAForever/java-guidelines/wiki/Contribution-Guidelines) before creating a pull request


# How to run

1. Clone the project with git
1. Open the project into IntelliJ Ultimate
1. Make sure you have the IntelliJ [Lombok plugin](https://plugins.jetbrains.com/idea/plugin/6317-lombok-plugin) installed
1. Make sure you have `Enable annotation processing` enabled in the settings
1. Run the Gradle task `:webview-patch build` to build the webview-patch JAR which is referenced by the run configurations
1. Run the Gradle task `:downlords-faf-client downloadNativeDependencies` to download the ICE adapter

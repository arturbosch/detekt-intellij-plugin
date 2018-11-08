# IntelliJ Detekt Plugin

[![Join the chat at https://kotlinlang.slack.com/messages/C88E12QH4/convo/C0BQ5GZ0S-1511956674.000289/](https://img.shields.io/badge/chat-on_slack-red.svg?style=flat-square)](https://kotlinlang.slack.com/messages/C88E12QH4/convo/C0BQ5GZ0S-1511956674.000289/)
[![build status](https://travis-ci.org/arturbosch/detekt-intellij-plugin.svg?branch=master)](https://travis-ci.org/arturbosch/detekt-intellij-plugin)
[![build status windows](https://ci.appveyor.com/api/projects/status/5pfg19cd9qxhsj02/branch/master?svg=true)](https://ci.appveyor.com/project/arturbosch/detekt-intellij-plugin)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Farturbosch%2Fdetekt-intellij-plugin.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Farturbosch%2Fdetekt-intellij-plugin?ref=badge_shield)

Integrates _detekt_, a static code analysis tool for the Kotlin programming language, into IntelliJ.

The plugin can be downloaded from the [Jetbrains plugin repository](https://plugins.jetbrains.com/plugin/10761-detekt).

## Enabling the plugin
Once you have installed the plugin, navigate to Settings/Preferences -> Tools -> Detekt. From there you will see the following screen, where you can specify your Detekt configuration file and enable it for your project. Warnings will be displayed in each file.

![detekt in action](./img/detekt.png "detekt in action")

## Building the plugin

For building the project, the [Gradle IntelliJ plugin](https://github.com/JetBrains/gradle-intellij-plugin)
is used.

```bash
# linux & macOS
./gradlew buildPlugin
# windows
gradlew buildPlugin
```


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Farturbosch%2Fdetekt-intellij-plugin.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Farturbosch%2Fdetekt-intellij-plugin?ref=badge_large)

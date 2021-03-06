# Slaq

Unoffical [Slack](https://slack.com/) client that doesn't eat all your RAM.
Current implementation of Slaq uses 3x less memory for same teams opened

Based on [Slackfish](https://github.com/markussammallahti/harbour-slackfish).

## How to use
Get latest Qt framework. 
Minimum required version is Qt 5.11.

Note: QtWebEngine module must be installed during the Qt framework installation

Minimun GCC version is 5.x (Linux)

We recommends online installer [here](https://www.qt.io/download-qt-installer)

or download offline versions:
[Linux](http://download.qt.io/official_releases/qt/5.11/5.11.1/qt-opensource-linux-x64-5.11.1.run), [Windows](http://download.qt.io/official_releases/qt/5.11/5.11.1/qt-opensource-windows-x86-5.11.1.exe), [macOS](http://download.qt.io/official_releases/qt/5.11/5.11.1/qt-opensource-mac-x64-5.11.1.dmg)

Note: currently tested only on Linux

Compile, build and run: `qmake && make && ./slaq`

Privacy policy, because that is necessary: We don't connect to anything apart from Slack.

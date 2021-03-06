## Explore

### *Instructions for building QT from source code*

> DMM

<br/>

#### Which platforms can be used by Qt

- [Supported Platforms | Qt 5.11](http://doc.qt.io/qt-5/supported-platforms.html)
- [Building Qt Sources | Qt 5.11](http://doc.qt.io/qt-5/build-sources.html)

<br/>

#### Windows

##### Prepare

- [Qt for Windows - Requirements | Qt 5.11](http://doc.qt.io/qt-5/windows-requirements.html)
- [Qt for Windows - Building from Source | Qt 5.11](http://doc.qt.io/qt-5/windows-building.html)

<br/>

###### Install tools which are required for building Qt 5 from source

- [Perl](https://www.activestate.com/activeperl/downloads) version 5.12 or later
- [Python](https://www.python.org/downloads/windows/) version 2.7 or later
- [Ruby](https://rubyinstaller.org/downloads/) version 1.9.3 or later

Remember to append these software's folders to ```PATH``` environment variable(Some installer will do it by default or your choice).

<br/>

###### Install C++ compiler

- [MinGW-builds gcc](http://mingw-w64.org/doku.php/download/mingw-builds) 4.9 or later
- [Visual Studio](https://visualstudio.microsoft.com/) 2012 or later

<br/>

Ref:

- [MinGW vs MinGW-W64及其它 - Bouygues - 博客园](https://www.cnblogs.com/bouygues/p/6072991.html)

Ref++:

- [Announcing Visual C++ Build Tools 2015 &ndash; standalone C++ tools for build environments | Visual C++ Team Blog](https://blogs.msdn.microsoft.com/vcblog/2015/11/02/announcing-visual-c-build-tools-2015-standalone-c-tools-for-build-environments/)

<br/>

###### Download and extract the source of Qt

- Go to [Download Offline Installers - Qt](https://www1.qt.io/offline-installers/?hsLang=en), and find **Source packages & Other releases**.
- *Uncompress the files into the directory you want Qt installed; e.g. ```C:\Qt\5.11```.*

<br/>

##### Configure, Compile and Install

###### Configure

[Qt Configure Options | Qt 5.11](http://doc.qt.io/qt-5/configure-options.html)

...

<!--
Copyright 2016 Development Entropy (deventropy.org) Contributors

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

# Development Entropy

Development Entropy or _deventropy_ is a playground for software projects. These mostly obscure projects are either
things that have been helpful to me at some point and hopefully help someone else; or these are projects that explore
ideas I've had.

### Why not use the user space in GitHub

Simply I did not want `io.github.bindul` or `name.bindul` as Group IDs of projects in a public repository. So, lets use
`org.deventropy`.

## Projects

The collection has the following project's at this time...

| Project | Status | Summary |
|---------|--------|---------|
| [JUnit Helper](./junit-helper/) | In development | A collection of modules to help write / run JUnit tests; specially when using _server_ like resources like Derby database, HTTP server, etc. |
| [Script Packager](./script-packager/) | Idea | An idea to manage *nix shell script sources, reuse script modules, etc. Package and generate deployments using maven. |
| [Shared Utils](./shared-utils/) | In development | Shared classes across the projects above. |
| [Site Skins](./site-skins/) | Idea | A proposed skin and tools based on Bootswatch/Bootstrap and Velocity, to replace the current `reflow-maven-skin` which is no longer being maintained and does not support newer versionf of `maven-site-plugin`. |
| Deventropy Parent | In development | Parent project, shared code quality configs, etc. |
| [Infix](http://infix.deventropy.org) | Idea | A collection of useful Maven plugins. _Possibly will get folded into deventropy_ | 

## Source Code, Issue Tracker, Binary Distribution etc.

The projects are hosted on GitHub. See the [Deventropy GitHub organization](https://github.com/deventropy/) for source
code, issue tracker, etc.

The project uses [Travis CI's](http://travis-ci.org/) free service for open source projects for continuous integration.
See the [organization's Travis CI page](https://travis-ci.org/deventropy/) for build status and details.

Most projects use [AppVeyor's](https://www.appveyor.com/) free service for open source projects for continuous
integration builds on the Windows environment. AppVeyor does not have a public team page, but each project using
AppVeyor builds will have a badge linking to the projects's AppVeyor page.

The project uses [Coveralls'](http://coveralls.io/) free service for open source projects for tracking unit test
coverage. See the [organization's Coveralls page](https://coveralls.io/github/deventropy/) for build status and
details.

The project uses [Codacy's](https://www.codacy.com/) and [Coverity's](http://www.coverity.com/) free service for open
source projects for static code analysis. See the individual project's badge link to see the project's Codacy and
Coverity pages.

The project uses [VersionEye's](https://www.versioneye.com/) free service for open source projects for tracking
dependency and plugin versions. See the [organization's VersionEye page](https://www.versioneye.com/organisations/deventropy/projects)
for the projects being tracked.

### <a name="repository"></a>Binary Distribution Repository

The project is built using [Apache Maven&reg;](http://maven.apache.org/) and binaries are available through the
[JFrog Open Source Software](https://oss.jfrog.org/webapp/#/home) service.

To get the Snapshot and Release artifacts for this project, you may have to add the JFrog OSS repositories (below) to
your project's POM or local settings or as a proxy in a local repository manager.

* **Snapshot Repository:** https://oss.jfrog.org/artifactory/libs-snapshot
* **Release Repository:** https://oss.jfrog.org/artifactory/libs-release

Released versions are also available on the organization's [JFrog Bintray Repository](https://dl.bintray.com/deventropy/repository).

### Mailing Lists

Until such time that GitHub provides mailing list facilities; the project has a SourceForge [project](https://sourceforge.net/projects/deventropy/)
and the [Mailing Lists](https://sourceforge.net/p/deventropy/lists/) there.

## Attributions

All the work in this site and the associated hosted _organizations_ on GitHub, SourceForge, BinTray, etc. have been
developed by me and other contributors to the projects. This work is free and open source, licensed primarily under the
[Apache Software License version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt).

This site or software are my personal views and work; and does not in any way represent the views or opinions of my
employer or past employers.

---
title: SonarQube License-Check 1.0 Beta
date: 2016-10-10 18:00:00
author: Christian Köberl
subtitle: First beta of new plugin for SonarQube to check software licenses. 
---

We are happy to announce our new plugin to check software dependencies for licenses in SonarQube: [SonarQube License-Check](https://github.com/porscheinformatik/sonarqube-licensecheck).

## Rewrite and new name

We were forced to rewrite our [Dependency Check Sonar Plugin](https://github.com/porscheinformatik/sonar-dependency-check-plugin) because [SonarQube](http://www.sonarqube.org/) changed a lot of internals - including the removal of any dependencies between components.

The successor is called "SonarQube License-Check". Two reasons for the rename: first, our plugin actually checks licenses and there was a name clash with the [Dependency-Check Plugin for SonarQube](https://github.com/stevespringett/dependency-check-sonar-plugin).

## Beta-phase

The first release is just a beta - but we are already using the plugin on our production SonarQube. We hope to release the first release in October 2016.
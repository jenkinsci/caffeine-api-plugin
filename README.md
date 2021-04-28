# caffeine-api-plugin
[Caffeine](https://github.com/ben-manes/caffeine) packaged as a Jenkins plugin for use by other plugins.

## Important information for plugin developers

This plugin currently hosts the 2.x line of Caffine.  The 3.x line has some minor API breakage and to ensure that you do not fall fowl of this when the plugin is upgraded you should follow the following rules.

1. Do not use any API that has been marked as `deprecated`
2. Avoid any API that is flagged as "incompatable" in the [release notes](https://github.com/ben-manes/caffeine/releases/tag/v3.0.0)

for some more information see [this GitHub issue](https://github.com/ben-manes/caffeine/issues/543)

## Maintainer Information

This plugin does not use `maven-release-plugin` but is released automatically on merging to the `master` branch using [JEP-229](https://github.com/jenkinsci/jep/blob/master/jep/229/README.adoc).

# Custom Build Helper Maven Plugin
 
This is a custom build helper pluginb based on the [build-helper-maven-plugin](http://www.mojohaus.org/build-helper-maven-plugin/) contains
serveral goals to support you in different kinds of task, like parsing version information,
add supplemental source/test folders to a Maven project or attach supplemental artifacts.

More details can be found on the [goals overview page]().

## Releasing

* Execute `mvn -B release:prepare release:perform`

For publishing the site do the following:

```
cd target/checkout
mvn verify site site:stage scm-publish:publish-scm
```

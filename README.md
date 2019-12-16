# Purpose
This project should help scripting developers develop their Groovy Scripts within their favorite IDE against their target Liferay version as defined by `targetVersion` in the build.gradle.

![Intellij LR Context Support](https://user-images.githubusercontent.com/20643732/70930300-7ac16080-1ffa-11ea-8018-b3bab197a57d.gif)

# To Use
```
git clone git@github.com:SGM3/LiferayGroovyContextSupport.git
```
Import the project into you favorite IDE.

Then simply add any new Groovy file (or use `GroovtTestIt.groovy`) in `src/main/groovy`, add the import for mocked objects `import static internal.MockObjects.*` and enjoy the benefits :grin: .

### Special Thanks
To Allen Ziegenfus for giving me the idea.

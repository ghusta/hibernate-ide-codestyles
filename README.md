# hibernate-ide-codestyles

This repository contains the IDE settings for Eclipse and IntelliJ IDEA.

Import these in your IDE if you plan to make changes to the Hibernate source code,
so that you can follow consistent formatting and style conventions with every
other contributor.

## Importing in IDEA

Copy the `hibernate_orm.xml` style file in your IDEA configuration.

The path on OSX is:

 - ~/Library/Preferences/IdeaIC14/codestyles/

On Linux it is:
 - ~/.IntelliJIdea2016.3/config/codestyles

On Windows:
 - %USERPROFILE%\\.IntelliJIdea2016.3\config\codestyles

See help online: [Copying Code Style Settings](https://www.jetbrains.com/help/idea/2016.3/copying-code-style-settings.html).

### Importing code styles can also be done through the UI

To do so:

 * go to `IntelliJ IDEA` -> `Preferences` on a Mac or `File` -> `Settings` on Windows
 * then to `Editor` -> `Code Style` -> `Java` and click `Manage`
 * in the `Code Style Schemes` dialog, press `Import` and add the provided XML file
 * after that, select the imported schema from the `Schema` dropdown

See help online: [Code Style](https://www.jetbrains.com/help/idea/2016.3/code-style.html). 

### Another alternative 

Use the plugin [Eclipse Code Formatter for IntelliJ IDEA](https://plugins.jetbrains.com/idea/plugin/6546-eclipse-code-formatter).

It solves the problem of maintaining a common code style in team environments where both IDEA and Eclipse are used.
 
## Importing in Eclipse

In Eclipse, you import the three provided files from within the UI.
Open menu `Window` -> `Preferences`; then open section `Java` -> `Code Style`.
You'll see three sub sections:
 - Clean Up
 - Code Templates
 - Formatter

Each of these has a separate `Import` button; import the provided xml files
and then mark them as active in the current profile.

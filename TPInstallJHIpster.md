## create folder and command : "jhipster"

? Which _type_ of application would you like to create? Monolithic application (recommended for simple projects)
? What is the base name of your application? blog
? What is your default Java package name? com.macrosoftas.blog
? Do you want to use the JHipster Registry to configure, monitor and scale your application? No
? Which _type_ of authentication would you like to use? JWT authentication (stateless, with a token)
? Which _type_ of database would you like to use? SQL (H2, MySQL, MariaDB, PostgreSQL, Oracle, MSSQL)
? Which _production_ database would you like to use? PostgreSQL
? Which _development_ database would you like to use? H2 with disk-based persistence
? Do you want to use the Spring cache abstraction? Yes, with the Ehcache implementation (local cache, for a single node)

? Do you want to use Hibernate 2nd level cache? Yes
? Would you like to use Maven or Gradle for building the backend? Maven
? Which other technologies would you like to use? (Press <space> to select, <a> to toggle all, <i> to invert selection)
? Which _Framework_ would you like to use for the client? Angular
? Would you like to use a Bootswatch theme (https://bootswatch.com/)? Default JHipster
? Would you like to enable internationalization support? Yes
? Please choose the native language of the application French
? Please choose additional languages to install English, German
? Besides JUnit and Jest, which testing frameworks would you like to use? Gatling, Cucumber, Protractor
? Would you like to install other generators from the JHipster Marketplace? No

Installing languages: fr, en, de

## JDL /jh

By default import-jdl regenerates only entities which have changed, if you want all your entities to be regenerated then pass in the --force flag. Please note that this will overwrite all your local changes to the entity files
jhipster import-jdl ./my-jdl-file.jdl --force

## UML to Jhipster

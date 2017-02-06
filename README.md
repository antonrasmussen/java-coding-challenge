# java-coding-challenge

This is a small Java coding challenge that we normally ask all candidates to complete in order to help us better assess their coding abilities. The challenge is designed to hopefully not take more than 1-2 hours of your time. The challenge is also designed to be aligned with the [Clinical Trials Reporting Program](https://www.cancer.gov/about-nci/organization/ccct/ctrp) project at [CBIIT](https://github.com/CBIIT), on which you most likely will be working on. The instructions are as follows.

Please setup a local database and populate it using [database-postgres.sql](database-postgres.sql) script. Please feel free to use a database vendor of your choice; [database-postgres.sql](database-postgres.sql) defines a single table with a little bit of sample data. What we are looking from you is a simple deployable Java Web application that displays content of the `clinical_trial` table on a Web page.

Here are some additional implementation notes:
* Use a build tool of your choice -- Maven, Ant, Gradle -- or no build tool at all, if that's more convenient for you (perhaps you'd want to use your IDE's capabilities to generate a project structure). If using Maven, [maven-archetype-webapp](https://maven.apache.org/plugins-archives/maven-archetype-plugin-1.0-alpha-7/examples/webapp.html) might be helpful. 


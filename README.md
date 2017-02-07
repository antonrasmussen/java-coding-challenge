# java-coding-challenge

This is a small Java coding challenge that we normally ask all candidates to complete in order to help us better assess their coding abilities. The challenge is designed to hopefully not take more than 1-2 hours of your time. The challenge is also designed to be aligned with the [Clinical Trials Reporting Program](https://www.cancer.gov/about-nci/organization/ccct/ctrp) project at [CBIIT](https://github.com/CBIIT), on which you most likely will be working on. The instructions are as follows.

Please set up a local database and populate it using [database-postgres.sql](database-postgres.sql) script. Please feel free to use a database vendor of your choice; [database-postgres.sql](database-postgres.sql) defines a single table with a little bit of sample data. What we are looking from you is a simple deployable Java Web application that displays content of the `clinical_trial` table on a Web page in tabular form.

Here are some additional implementation notes:
* Use a build tool of your choice -- Maven, Ant, Gradle -- or no build tool at all, if that's more convenient for you (perhaps you'd want to use your IDE's capabilities to simply generate a project structure). If using Maven, [maven-archetype-webapp](https://maven.apache.org/plugins-archives/maven-archetype-plugin-1.0-alpha-7/examples/webapp.html) might be helpful.
* Please select an application architecture you're comfortable with. For example, it could be a "classic" Java EE application, or a Spring app, a Struts app, or a plain Web app backed by Servlets. 
* Obviously your application would need some kind of data access tier. [Hibernate](http://hibernate.org/) would be best (simply because it is being used in [CTRP](https://www.cancer.gov/about-nci/organization/ccct/ctrp), but not required: iBatis, EJB, Spring JDBC Template, or even plain JDBC would do.
* Ideally, your application would have a REST service that exposes JSON with clinical trials data to the Web browser. However, an approach where you'd render a complete HTML page in a JSP is also acceptable.
* Ideally, your Web page would utilize one of the popular Data Table components you're comfortable with (for example, [JQuery Data Tables](https://datatables.net/). Or, if you prefer, you could render HTML table markup directly in your JSP.
* Once done, please send us a link to your source code and to a deployable WAR or EAR file that could be dropped into Tomcat or JBoss.

We do understand your time is valuable and therefore tried to keep the scope of this challenge to 1-2 hours. The goal is to see your approach to the problem and your coding style rather than delivering a specific set of features.

Thank you for your interest in SemanticBits!



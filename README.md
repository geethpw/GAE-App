# GAE-App
Google App Engine Java(Spring) Sample Starter Application

This is a sample Java Maven Spring Web application with ready made configurations to get into coding straightaway.

Adding your Google App Engine Project ID:
1. open pom.xml
2. insert your project id in the :  <app.vid></app.id> tags
    for example:
    <properties>
        <app.id>my-sample-spring-gae-app</app.id>
        <app.version>1</app.version>
        <appengine.version>1.9.25</appengine.version>
        <gcloud.plugin.version>2.0.9.74.v20150814</gcloud.plugin.version>
        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
        <maven.compiler.showDeprecation>true</maven.compiler.showDeprecation>
    </properties>

Maven Details:
GroupId     : com.google.appengine.archetypes
ArtifactId  : appengine-skeleton-archetype
Version     : 2.0.2-1.9.25

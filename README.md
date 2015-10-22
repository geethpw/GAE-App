# GAE-App
Google App Engine Java(Spring) Sample Starter Application

This is a sample Java Maven Spring Web application with ready made configurations to get into coding straightaway.

Adding your Google App Engine Project ID: </br>
1. open pom.xml </br>
2. insert your project id in the : ```<app.vid></app.id> tags``` </br>

for example: </br>

```   
    <properties> </br>
        <app.id>my-sample-spring-gae-app</app.id> </br>
        <app.version>1</app.version> </br>
        <appengine.version>1.9.25</appengine.version> </br>
        <gcloud.plugin.version>2.0.9.74.v20150814</gcloud.plugin.version> </br>
        <project.build.sourceEncoding>UTF-8</project.build.sourceEncoding> </br>
        <maven.compiler.showDeprecation>true</maven.compiler.showDeprecation> </br>
    </properties> </br>
```

<b><u>Maven Details:</u></b></br>
<b>GroupId  </b>   : com.google.appengine.archetypes</br>
<b>ArtifactId</b>  : appengine-skeleton-archetype</br>
<b>Version  </b>   : 2.0.2-1.9.25</br>

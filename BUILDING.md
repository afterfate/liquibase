## Building Liquibase ##
Liquibase core is currently built using Maven 3.  Liquibase's modules are organized as follows

/                               Liquibase Parent Configuration pom
+ liquibase-core                       
+ liqubase-integration-tests   
+ liquibase-maven-plugin      
+ liquibase-osgi
+ samples
   + liquibase-ext-change
   + liquibase-ext-changewithnestedtags
   + liquibase-ext-sqlgenerator


Building with the <code>maven package</code> command will compile, run
tests and build the packages.

```
$ mvn package
[INFO] Reactor Summary:
[INFO] 
[INFO] Liquibase Parent Configuration
[INFO] Liquibase Core
[INFO] Liquibase Maven Plugin
[INFO] Liquibase Osgi
[INFO] Liquibase extension sample change
[INFO] Liquibase extension sample using nested tags for change
[INFO] Liquibase extension showing sample sqlgenerator
[INFO] Liquibase Integration Tests
```

## Known Issues ##


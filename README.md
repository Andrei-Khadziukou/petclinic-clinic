# Pet Clinic Service

## Configuration
* Add `management.security.enabled: false` property into `application.yml` file if you need to connect to secured endpoints from actuator (don't commit that configuration) 

# Running
Create database : configure gradle.properties
run gradlew createDatabase(for dropping run: gradlew dropDatabase)
Disable @EnableEurekaClient(move temporary bootstrap.yml) or run it
Run from project root: gradlew bootRun


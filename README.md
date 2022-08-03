# spring-boot-keycloak

The following is required for a working setup

1. keycloak server setup
Please find the docker-compose.yaml file for the setup in the utils directory
19.0.1

2. KEY-CLOAK.postman_collection.json
Postman collection for testing

3. UI setup
separate project
https://github.com/dev-full-stack-22/angular-keycloak-setup


Resources
The below article was used for configuring Spring Boot and KeyCloak for integration.
All the users and roles are based on the following article. As per this project, separate Realm Roles are not required as
Client Roles can be directly mapped to Users
https://medium.com/devops-dudes/securing-spring-boot-rest-apis-with-keycloak-1d760b2004e

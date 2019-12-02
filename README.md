# keycloakProject
get a keycloak server up and running on a cloud vm

select a VM with latest ubuntu and at least 2Gb (runs JBOSS)
latest docker image is no good for this propose at this time, run
sudo docker run -dp 8080:8080 -e KEYCLOAK_USER=admin0212 -e KEYCLOAK_PASSWORD=njb0212    jboss/keycloak:8.0.0

don't forget to open port 8080,
keycloak login is requesting https, need to set that up.

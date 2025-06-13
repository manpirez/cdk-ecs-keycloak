ARG FROM=quay.io/keycloak/keycloak

FROM ${FROM}

# We're simply going to replace the welcome page in the default theme.
COPY index.ftl /opt/jboss/keycloak/themes/keycloak/welcome/index.ftl
FROM docker-registry.default.svc:5000/openshift/wildfly
#FROM registry.access.redhat.com/jboss-eap-7/eap71-openshift

USER root:root
RUN chmod -R 777 /opt/eap/standalone/
USER wildfly

COPY maven/ /opt/eap/standalone/deployments/

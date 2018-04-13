FROM openshift/wildfly-81-centos7
#FROM registry.access.redhat.com/jboss-eap-7/eap71-openshift

USER root:root
RUN chmod -R 777 /wildfly/standalone/
USER wildfly

COPY maven/ /wildfly/standalone/deployments/

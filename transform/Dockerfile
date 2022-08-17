ARG ALFRESCO_TAG
FROM alfresco/alfresco-transform-core-aio:2.5.7

# default user is alfresco (added on the base image alfresco/alfresco-content-repository-community)
# change to root user to be able to install the addons and packages
USER root

RUN yum makecache
RUN yum -y install thai-scalable-tlwgtypo-fonts 
RUN yum -y install thai-scalable-tlwgmono-fonts

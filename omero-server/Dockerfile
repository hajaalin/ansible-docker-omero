FROM omero-base

ENV PLAYBOOK=/opt/omero-ansible/provisioning/build.yml
COPY build.yml $PLAYBOOK
 
RUN ansible-playbook $PLAYBOOK -c local

FROM ansible/centos7-ansible

# This playbook will clone the OMERO-Ansible repository
ENV provision=/provision.yml
COPY provision.yml $provision
RUN ansible-playbook $provision -c local

# cd to the cloned directory
WORKDIR /opt/omero-ansible/provisioning

FROM ansible/centos7-ansible

ENV provision=/provision.yml
COPY provision.yml $provision

RUN ansible-playbook $provision -c local


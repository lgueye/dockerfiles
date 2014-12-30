FROM lgueye/oracle-jdk8
MAINTAINER louis.gueye@gmail.com
ADD playbook.yml /tmp/playbook.yml
RUN ansible-playbook --inventory-file=/etc/ansible/hosts /tmp/playbook.yml
RUN echo "Done provisioning index component"




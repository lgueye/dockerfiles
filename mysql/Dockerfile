FROM lgueye/ansible
MAINTAINER louis.gueye@gmail.com
ADD playbook.yml /tmp/playbook.yml
ADD my.cnf.j2 /tmp/my.cnf.j2
RUN ansible-playbook --inventory-file=/etc/ansible/hosts /tmp/playbook.yml
RUN echo "Done provisioning data component"


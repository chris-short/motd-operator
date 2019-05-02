FROM quay.io/operator-framework/ansible-operator:v0.4.0

RUN ansible-galaxy install chris-short.ansible_role_motd

COPY roles/ ${HOME}/roles/
COPY watches.yaml ${HOME}/watches.yaml

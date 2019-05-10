FROM quay.io/chrisshort/operatortainer:v0.0.4

RUN ansible-galaxy install chris-short.ansible_role_motd

COPY roles/ ${HOME}/roles/
COPY watches.yaml ${HOME}/watches.yaml

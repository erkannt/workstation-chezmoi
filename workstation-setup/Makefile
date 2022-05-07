.phony: *

.DEFAULT_GOAL := ansible

ansible-lint:
	ansible-lint playbook.yaml

ansible: ansible-lint
	ansible-playbook playbook.yaml

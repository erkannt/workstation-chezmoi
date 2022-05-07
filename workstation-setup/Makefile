.phony: *

.DEFAULT_GOAL := ansible

lint:
	ansible-lint *.yaml

ansible: lint
	ansible-playbook all.yaml

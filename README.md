# Ansible Role: k8s_prometheus

[![Lint](https://github.com/dcjulian29/ansible-role-k8s_prometheus/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-k8s_prometheus/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-k8s_prometheus.svg)](https://github.com/dcjulian29/ansible-role-k8s_prometheus/issues)

This an Ansible role to deploy prometheus monitoring system into a Kubernetes cluster.

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.k8s_prometheus
  src: https://github.com/dcjulian29/ansible-role-k8s_prometheus.git
  version: main
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None

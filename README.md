<!--
SPDX-FileCopyrightText: 2023 - 2025 Slavi Pantaleev
SPDX-FileCopyrightText: 2025 Suguru Hirahara

SPDX-License-Identifier: AGPL-3.0-or-later
-->

# LiveKit Server Ansible role

[![REUSE status](https://api.reuse.software/badge/github.com/mother-of-all-self-hosting/ansible-role-livekit-server)](https://api.reuse.software/info/github.com/mother-of-all-self-hosting/ansible-role-livekit-server)

This is an [Ansible](https://www.ansible.com/) role which installs [LiveKit Server](https://docs.livekit.io/home/) to run as a [Docker](https://www.docker.com/) container wrapped in a systemd service.

This role *implicitly* depends on:

- [`com.devture.ansible.role.playbook_help`](https://github.com/devture/com.devture.ansible.role.playbook_help)
- [`com.devture.ansible.role.systemd_docker_base`](https://github.com/devture/com.devture.ansible.role.systemd_docker_base)

Check [defaults/main.yml](defaults/main.yml) for the full list of supported options.

💡 See this [document](docs/configuring-livekit-server.md) for details about setting up the service with this role.

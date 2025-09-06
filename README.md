# dockerfiles-kali

Dockerfiles to build Kali images. See [straysheep-dev/docker-configs](https://github.com/straysheep-dev/docker-configs) for a general overview and references.

> [!NOTE]
> These files were built from a combination of:
> - [Official Kali Linux Docker Images](https://www.kali.org/docs/containers/official-kalilinux-docker-images/)
> - [geerlingguy's](https://github.com/geerlingguy) `docker-<os>-ansible` templates
> - [Molecule's systemd-enabled container guide](https://ansible.readthedocs.io/projects/molecule/guides/systemd-container/)
> - [Rocky Linux Docker image systemd integration notes](https://hub.docker.com/r/rockylinux/rockylinux#systemd-integration)
> - Searching for, and reviewing, examples and documentation with ChatGPT or AI mode Google Search


## Images

| Version | Components and Software | Status |
| :--- | :---: | :---: |
| `kalilinux/kali-rolling:latest` | `systemd` | ![Static Badge](https://img.shields.io/badge/supported-green) |


## License

[MIT](LICENSE)
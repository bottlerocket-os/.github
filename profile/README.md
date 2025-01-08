# Bottlerocket

Bottlerocket is a Linux-based operating system optimized for hosting containers.
It’s free and open-source software, developed in the open here on GitHub.
Bottlerocket is installed as the base operating system on the machine or instance where your containers themselves are running.
It is specifically designed to work with your container orchestrator (like Kubernetes) to automate the lifecycle of the containers running in your cluster.
Bottlerocket runs in the cloud or in your datacenter.

## Project Navigation

The `bottlerocket-os` GitHub organization contains a number of repos. Feel free to examine everything, but most people are looking for the following:

| Repository | Description |
| ---- | ----------- |
| [`bottlerocket-os/bottlerocket`](https://github.com/bottlerocket-os/bottlerocket) | Operating system images and tools |
| [`bottlerocket-os/bottlerocket-core-kit`](https://github.com/bottlerocket-os/bottlerocket-core-kit) | Core operating system packages |
| [`bottlerocket-os/bottlerocket-kernel-kit`](https://github.com/bottlerocket-os/bottlerocket-kernel-kit) | Linux kernels, bootloaders, firmware |
| [`bottlerocket-os/bottlerocket-project-website`](https://github.com/bottlerocket-os/bottlerocket-project-website) | Bottlerocket's documentation on [bottlerocket.dev](https://bottlerocket.dev/) |
| [`bottlerocket-os/bottlerocket-control-container`](https://github.com/bottlerocket-os/bottlerocket-control-container) | Control host container bundled with ECS and Kubernetes AWS variants |
| [`bottlerocket-os/bottlerocket-admin-container`](https://github.com/bottlerocket-os/bottlerocket-admin-container) | Admin host container  |
| [`bottlerocket-os/bottlerocket-update-operator`](https://github.com/bottlerocket-os/bottlerocket-update-operator) | Kubernetes operator that automates updates to Bottlerocket |
| [`bottlerocket-os/bottlerocket-ecs-updater`](https://github.com/bottlerocket-os/bottlerocket-ecs-updater) | Service to automatically manage Bottlerocket updates in an Amazon ECS cluster |

## Getting involved in the Bottlerocket Community

- **Want to connect with others in the project?** [Join the Meetup group](https://www.meetup.com/bottlerocket-community/) and attend community meetings.
- **Got a question?** Ask in our [discussions forum](https://github.com/bottlerocket-os/bottlerocket/discussions).
- **Find a bug or suggest an improvement?** File an issue on the appropriate repo (just use [`bottlerocket-os/bottlerocket` issues](https://github.com/bottlerocket-os/bottlerocket/issues/new/choose) if you're unsure of where the issue goes).
- **Have some code to contribute?** Read our [contributing document](https://github.com/bottlerocket-os/bottlerocket/blob/develop/CONTRIBUTING.md).
- **Find a potential security issue?** Don't create a public issue on GitHub, see [SECURITY.md](https://github.com/bottlerocket-os/.github/blob/master/SECURITY.md) for the appropriate process.

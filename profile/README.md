# Bottlerocket

Bottlerocket is a Linux-based operating system optimized for hosting containers.
It’s free and open-source software, developed in the open here on GitHub.
Bottlerocket is installed as the base operating system on the machine or instance where your containers themselves are running.
It is specifically designed to work with your container orchestrator (like Kubernetes) to automate the lifecycle of the containers running in your cluster.
Bottlerocket runs in the cloud or in your datacenter.

## Project Navigation

The `bottlerocket-os` GitHub organization contains a number of repos. Feel free to examine everything, but most people are looking for the following:

- [`bottlerocket-os/bottlerocket`](https://github.com/bottlerocket-os/bottlerocket) the source to the operating system and associated tools.
- [`bottlerocket-os/bottlerocket-update-operator`](https://github.com/bottlerocket-os/bottlerocket-update-operator) the source for the Kubernetes operator that automates updates to Bottlerocket.
- [`bottlerocket-os/bottlerocket-ecs-updater`](https://github.com/bottlerocket-os/bottlerocket-ecs-updater) the source for the service to automatically manage Bottlerocket updates in an Amazon ECS cluster.
- [`bottlerocket-os/bottlerocket-control-container`](https://github.com/bottlerocket-os/bottlerocket-control-container) the source for the control host container bundled with ECS and Kubernetes  AWS variants.
- [`bottlerocket-os/bottlerocket-control-container`](https://github.com/bottlerocket-os/bottlerocket-control-container) the source for the  admin host container.
- [`bottlerocket-os/bottlerocket-project-website`](https://github.com/bottlerocket-os/bottlerocket-project-website) the source for Bottlerocket's documentation on [bottlerocket.dev](https://bottlerocket.dev/).

## Getting involved in the Bottlerocket Community

- **What to connect with others in the project?** [Join the Meetup group](https://www.meetup.com/bottlerocket-community/) and attend community meetings.
- **Got a question?** Ask in our [discussions forum](https://github.com/bottlerocket-os/bottlerocket/discussions).
- **Find a bug or suggest an improvement?** File an issue on the appropriate repo (just use [`bottlerocket-os/bottlerocket` issues](https://github.com/bottlerocket-os/bottlerocket/issues/new/choose) if you're unsure of where the issue goes).
- **Have some code to contribute?** Read our [contributing document](https://github.com/bottlerocket-os/bottlerocket/blob/develop/CONTRIBUTING.md).


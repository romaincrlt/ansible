# podman

This role installs the `podman` package.

It enables **linger** (via `loginctl`) for the **ansible_user**.

The task `podman_restart` can be called to enable the `podman-restart` service for the **ansible_user**,
to manage the pod lifecycle with a pod YAML definition.

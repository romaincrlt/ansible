# podman

This role installs the `podman` package.

It enables **linger** (via `loginctl`) for the **ansible_user**.

To enable the `podman-restart.service` for the **ansible_user**, set the variable `enable_podman_restart_service` to **true**.
Do not activate it when managing containers with **systemd**.

To enable the `podman.socket` for the **ansible_user**, set the variable `enable_podman_socket` to **true**.

# Security

This deployment is meant for internal use only. It also assumes all of the devices which can access it are considered "Safe".

If you require the upmost in security and hardening, this isn't for you.

Insecure practices used:
- Adding the user to the `Docker` group
  - This allows the user to use `docker` commands, without having to use `sudo`, etc.
  - (THIS DOES NOTHING SO FAR) TODO: Disable `addusertodockergroup` to mitigate this.
  - https://docs.docker.com/engine/install/linux-postinstall/#manage-docker-as-a-non-root-user
  - https://docs.docker.com/engine/security/#docker-daemon-attack-surface
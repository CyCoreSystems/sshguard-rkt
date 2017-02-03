# sshguard-rkt
systemd unit for executing sshguard in rkt

This is simply an example systemd unit which runs @mischief's sshguard docker container in `rkt`.

To use it:
  1. drop the unit file into `/etc/systemd/system/`
  2. enable it at boot:  `systemctl enable sshguard`
  3. start it presently: `systemctl start sshguard`
  

See [coreos-sshguard](https://github.com/CyCoreSystems/coreos-sshguard) for a
complete setup, forked from @mischief

# WIP!! Work in progerss, nothing is working here!

From Rspamd >2.8 (as of July 2021 not yet released) it's possibile to use Rspamd external services configuration to query Pyzor service (see [Rspamd external services module](https://rspamd.com/doc/modules/external_services.html#pyzor-specific-details)).  

With this repo or better, Docker Hub image (not yet released), we can start a Pyzor service based on Ubuntu OS.  

## Usage (not yet working)
docker run -d -p 127.0.0.1:5953:5953 --tmpfs /tmp --tmpfs /run --tmpfs /run/lock -v /sys/fs/cgroup:/sys/fs/cgroup:ro --name pyzor-cc-systemd pyzor-cc-systemd

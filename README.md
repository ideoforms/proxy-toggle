proxy-toggle
============

proxy-toggle: OS X shell script to toggle web proxying through an ssh host,
              for secure browsing that appears to come from elsewhere.

Requires a remote host with ssh access.

To avoid password prompts, generate a public key and add it to the remote hosts'
	~/.ssh/authorized_keys

Makes use of SSH's SOCKS tunneling capabilities:
http://www.linuxjournal.com/content/use-ssh-create-http-proxy

Daniel Jones <http://www.erase.net/>

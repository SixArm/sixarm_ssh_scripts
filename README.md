# SSH » Scripts for secure shell

SSH scripts for secure shell:

  * `ssh-copy-id-help`: SSH script to copy a pub id file to a remote server into your authorized_keys.
  * `ssh-remove-known-host`: SSH script to remove a known host.
  * `ssh-set-directory-permissions`: Set the correct directory permissions of the current user's ~/.ssh directory.
  * `ssh-with-password`: Use SSH with preferred authentications set to use a password.

SSH key generation:

  * `ssh-keygen-with-email`: Generate our typical key with RSA 4096 and email address comment.
  * `ssh-keygen-with-email-xid-automation`: Generate our typical keys, with automation, and save using our typical file names.
  * `ssh-keygen-with-email-xid-passphrase`: Generate our typical keys, with passphrase, and save using our typical file names.

SSH key fingerprints:

  * `ssh-fingerprints-of-remote-host`: Print any host's SSH fingerprints.
  * `ssh-fingerprints-of-local-host`: Print local host's own /etc public key fingerprints.
  * `ssh-keygen-polyfill-l-f-sha`: Polyfill `ssh-keygen -l -f` to print SHA 256 fingerprints.

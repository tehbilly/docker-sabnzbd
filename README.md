Simple installation of sabnzbd on debian from the `wheezy` repositories.

The container exposes port `80` and the default volume would be at `/data`, so I recommend running the container with
`docker run -d -p 80 -v /some/path/sabnzbd:/data tehbilly/sabnzbd`. Visit http://localhost:{MAPPED_PORT} to start the
installation wizard.

Arch based Xlibre binary packages repository
--------------------------------------------

This repository can be enabled with the following actions:

* Run commands:\
  `sudo curl -sS https://raw.githubusercontent.com/artist4xlibre/packages-arch-based/refs/heads/main/0x73580DE2EDDFA6D6.gpg | gpg --import -`\
  `sudo pacman-key --lsign-key 73580DE2EDDFA6D6`
* Add the xlibre repository by adding this section to file /etc/pacman.conf:\
  `[xlibre]`\
  `Server = https://raw.githubusercontent.com/artist4xlibre/packages-arch-based/refs/heads/main`\
  `# List of available packages: https://github.com/artist4xlibre/packages-arch-based`

\
_artist for Xlibre_


# Torrent Files for Sailfish OS Releases
This repository is a collection of torrent files for older Sailfish OS releases.

### Contribution
If you still have older releases of Sailfish OS available you can contribute to this project:

- Create a pull request with your torrent files
- Provide a download link of either the release zip or the torrent file by creating an Issue on GitHub or contact me over [OpenRepos.net](https://openrepos.net/users/blacksheepdev)


### Creating a torrent file
The easiest way is to use mktorrent command line utility:

> mktorrent -a http://tracker.opentrackr.org:1337/announce -l 22 -s PATH-TO-YOUR-RELEASE.zip

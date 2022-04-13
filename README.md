# FDS-Github-Guide
Guidelines for FDS projects, please follow these rules as much as possible.

## Projects

### Owners

Each active project should have a maintainer assigned. Maintainers responsibilities are the following:

 - Maintain pull requests in a timely manner. Pull requests should be commented on positively and respecfully and merged or closed.
 - Maintain branches. Long list of os stale branches are a cruft.
 - Work with SecOps/DevOps on security issues. Try to patch high vurneable software in a timely manner.
 - Try to have a overlook of the opened issues. Similar to PR but lower priority.


## Branches

### Master branch: "master"

Master branches are considered "production" branches and are autodeployed to primary websites (without .dev.). For swarm connected projects this means that master branches deploy or are connected to swarm mainnet network.
We try to avoid pushing single commits to this branch, but rather "releases" or branch merges.

### Development branch: "development"

Development branches are testing/development branches. Any commits to master branch must be pushed here first. Projects are deployed to "dev" domains. (ie. app.fairdrive.**dev**.fairdatasociety.org). For swarm connected projects this means that development branches are deploying or are connecting to swarm testnet network.

#### master projects (which are also autodeployed)

 - https://github.com/fairDataSociety/fairOS-dfs --> [FairOS DFS](https://fairos.fairdatasociety.org)
 - https://github.com/fairDataSociety/gateway --> [Swarm Gateway](https://gateway.fairdatasociety.org)
 - https://github.com/fairDataSociety/Fairdrop --> [Fairdrop](https://fairdrop.fairdatasociety.org)
 - https://github.com/fairDataSociety/fds-blog --> [BLOG](https://blog.fairdatasociety.org/) **still ON Amazon!
 - https://github.com/fairDataSociety/galileo --> [Galileo](https://app.galileo.fairdatasociety.org)
 - https://github.com/fairDataSociety/fairdrive-theapp --> [Fairdrive-app](https://app.fairdrive.fairdatasociety.org)
 - https://github.com/fairDataSociety/dr-viewer --> [Consent](https://app.crviewer.fairdatasociety.org)
 - https://github.com/fairDataSociety/fairdrive-landing-page --> [Fairdrive-www](https://fairdrive.fairdatasociety.org)
 - https://github.com/fairDataSociety/dracula.me --> [Dracula.ME](https://app.dracula.fairdatasociety.org)
 - https://github.com/fairDataSociety/fairdrive-apps-photoalbum ---> [Photoalbum](https://app.photo.fairdatasociety.org)
 - https://github.com/fairDataSociety/fairOS-docs.git ---> [FairOS Docs](https://docs.fairos.fairdatasociety.org)

#### Development projects (which are also autodeployed)

 - https://github.com/fairDataSociety/fairOS-dfs --> [FairOS DFS](https://fairos.dev.fairdatasociety.org)
 - https://github.com/fairDataSociety/gateway --> [Swarm Gateway](https://gateway.dev.fairdatasociety.org)
 - https://github.com/fairDataSociety/Fairdrop --> [Fairdrop](https://fairdrop.dev.fairdatasociety.org)
 - https://github.com/fairDataSociety/galileo --> [Galileo](https://app.galileo.dev.fairdatasociety.org)
 - https://github.com/fairDataSociety/fairdrive-theapp --> [Fairdrive-app](https://app.fairdrive.dev.fairdatasociety.org)
 - https://github.com/fairDataSociety/dr-viewer --> [Consent](https://app.crviewer.dev.fairdatasociety.org)
 - https://github.com/fairDataSociety/fairdrive-landing-page --> [Fairdrive-www](https://fairdrive.dev.fairdatasociety.org)
 - https://github.com/fairDataSociety/dracula.me --> [Dracula.ME](https://app.dracula.dev.fairdatasociety.org)
 - https://github.com/fairDataSociety/fairdrive-apps-photoalbum ---> [Photoalbum](https://app.photo.dev.fairdatasociety.org)

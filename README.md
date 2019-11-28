# build-tools
* jam-rebuild: simple git pull in a JAM stack app (static website, no calls to backend other than a simple contact form or comment post)
* npm-rebuild: more complex, first updates repo, checks if there's any changes, and if there are rebuilds with npm and then restarts the process with the associated portnumber
## usage
* git clone https://github.com/ezhang7423/jamstack-build-tool.git
* replace the variables (&&variable&&) with your associated path and/or port number
* chmod a+x ./jam-rebuild
* chmod a+x ./npm-rebuild
to use in the future, simply cd to directory and either
* ./jam-rebuild
or 
* ./npm-rebuild

## todo
* add functionality that uses cron to auto update(CD/CI)

only works in linux/bash

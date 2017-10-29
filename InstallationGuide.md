### Installation Guide
To set the app in the swarm we need to follow the following steps
1. ./launcher network - to create the network for the service to use
2. ./launcher bootstrap data - to setup the data base
3. ./launcher bootstrap web_only - to setup the web app
4. ./launcher servicestart web_only - to set up the web app as a service
5. ./launcher scale - to scale the web_app to two containers
## Distelli example application

### Update an existing Server Distelli Agent to the latest version

This is an example repository exemplifying how to create an application, in Distelli, that, when deployed, will update a Distelli agent to the latest release.

### Disclaimer

This application is not supported by Distelli. **Use at your own risk.**

Concerns:
If you update the agent on your build server that is currently building, the build will be interupted.
Updates of the agent from some previous versions may interupt your deployed application briefly.

### How to use

1. Fork this repo
2. Create a new application (upgrade-agent) in Distelli that is connected to the forked repo.
3. Build the app
4. Deploy the app to your servers in Distelli that have older versions of the agent.
5. After a successful deploy run a "terminate" deploy. Otherwise Distelli will think there is an application deployed to these server(s) called "upgrade-agent".

We are here to help.
support@distelli.com





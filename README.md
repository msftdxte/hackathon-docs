# DevOps hackathon

## Team Members

- [Kevin Gjerstad](mailto:kevingj) 
- [Patrick Heyde](mailto:pheyde)
- [Nick Trogh](mailto:nicktrog)
- [Christian Geuer-Pollmann](mailto:chgeuer)

## Tooling

- Slack chat room. https://msftdxte.slack.com/messages/general/


## OIverall plan

dea for hackathon (just an idea): 
use feature flags to create version A & B of this sample app (can use same or different build agents)
include application insights for both versions
make changes to app with feature flag for version A and checkin
this kicks off a build and deployment (continous integration) for version A

20% of users will get version A, 80% will get directed to version B
http://blogs.msdn.com/b/mschray/archive/2015/07/16/azure-web-sites-a-b-testing-the-easy-way.aspx

Then we show off application insights telemetry data for each version
We can then promote the change to #allversions  







## Links mentioned during the talks

- The VSO build & Deploy tasks: https://github.com/Microsoft/vso-agent-tasks
- http://blogs.msdn.com/b/visualstudioalmrangers/archive/2015/09/16/version-control-guidance-alternative-branching-strategies.aspx


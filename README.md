# DevOps hackathon

- Infrastructure Setup
	- GitHub
	- Visual Studio Online
		- Kanban Board
	- Slack integrated w/ github & VSO
	- Azure
- Planning
- Adapted app to push metrics to Appliction Insights
- Build Definitions
	- CI
	- Unit Tests
- Custom Build Controller and Agents on VM in Azure
- Infrastructure as Code (ARM)
- Continuious Deployment from VSO to Azure Web Sites
- PowerBI for reporting on development velocity (VSO metrics)
- Azure Automation for monitoring and scaling SQL Azure DBs


## Team Members
 
- [Kevin Gjerstad](mailto:kevingj) kevingjerstad at live.com 
- [Patrick Heyde](mailto:pheyde) info at patrickheyde.de
- [Nick Trogh](mailto:nicktrog)  ntrogh at hotmail.com
- [Christian Geuer-Pollmann](mailto:chgeuer) chgeuer-fte at hotmail.com

```
	Team Name: Tail Spin Doctors
	Mission:   Insights-driven Testing in Production
```

## Azure Subscription 

Subscription ID: ´dd7941ee-db86-4b37-9ada-5742484412d0´

LID: msftdxte@outlook.com / pass ...

## Eval criteria

	1 Creativity / Geekyness
	2 3rd party / public re-usability
	3 Which DevOps practices were reused

## Tooling

- Application code: https://github.com/msftdxte/PartsUnlimited/
- Slack chat room: https://msftdxte.slack.com/messages/general/	
- Visual Studio Online: https://msftdxte.visualstudio.com/
	- https://msftdxte.visualstudio.com/DefaultCollection/DevOps%20Hackathon
		- currently internal GIT: https://msftdxte.visualstudio.com/DefaultCollection/_git/DevOps%20Hackathon
	- Slack Triggers: https://msftdxte.visualstudio.com/DefaultCollection/DevOps%20Hackathon/_admin/_servicehooks

## Overall plan

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

- [Using market place images in ARM templates](https://github.com/chgeuer/polopoly-on-azure/blob/master/ARM/polopoly-on-azure/Templates/LinuxVirtualMachine.json#L376)

- https://azure.microsoft.com/en-us/documentation/articles/resource-group-authoring-templates/
- https://azure.microsoft.com/en-us/blog/how-to-provision-and-deploy-multiple-websites-from-your-cloud-deployment-project/
- http://donovanbrown.com/post/2015/02/13/Do-you-Release-Management-take-this-feature-Deployment-Slots-to-be-your-DevOps-partner

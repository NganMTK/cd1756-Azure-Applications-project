# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- Costs:
	+ VMs: Costs depend on VM size, storage and network. VM can be more expensive because they are always on.
	+ App service: Pricing is based on the resource that you use. 

- Scalability:
	+ VMs: Can use both manual and auto scaling based on your configuation and management.
	+ App service: Setting auto scale (scale-in or scale-out) based on load and traffic
	
- Availability:
	+ VMs: flexibility than App service. However, VMs requires more operational overhead
	+ App service: easy to setup, manage and deploy
	
- Workflow:
	+ VMs: requires manage and setup on VMs
	+ App service: Build in features for integration deployment CI/CD.

- *Choose the appropriate solution (VM or App Service) for deploying the app*
	Choose App service
	
- *Justify your choice*
	Because:
		+ Flask app is a small app => easy to deploy and setup
		+ Low costs
		+ Can deploy via GIT

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
- Require higher security
- App develop with more feature and configuation
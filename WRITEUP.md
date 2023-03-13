# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.
##### Cost
    VM: Higher costs
    App service: pay as you go price
##### Scalability
    VM: Ability to access to server configuration
    App service: Can not access to server configuration, does not support multiple deployment
##### Availability
    VM: need to cluster multiple virtual machines to provide high availability
    App service: already supported high availability
##### Workflow
    VM: requires more effort with a extra steps
    App service: easy integrated in ci/cd of git 

=> Using App service because the application is quite simple, no need to install the specific apps or acess to server
### Assess app changes that would change your decision.

In case I have to control the operating system or application environment, or where the application requires a dedicated server for security or other reasons, then I will change my mind to use a VM.
